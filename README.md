                                   X86_64-linux-android
                                 cross-compile toolchian

To setup in android source folder

           git clone https://github.com/sayeed99/UBER-5.4.1.git prebuilts/gcc/linux-x86/x86/x86_64-linux-android-5.4.1 


Toolchain for x86/x86_64 architecture for android ROM compilation , compiled from Uber GCC 5.4.1 source with graphite and link time optimizations(lto).


                                 To enable ROM compilation



cherry-pick 

	In android source navigate to bionic

            https://github.com/sayeed99/android_bionic/commit/1b8c569054a8038551e895741a78ec3dc69348e5
 
	In android source navigate to build

            https://github.com/sayeed99/build/commit/f9197c35b734db93cab454dd96e52192bb182def

	In frameworks/base

            https://github.com/sayeed99/android_frameworks_base/commit/a5bc15a64736d42a9743b1f421f1d39c88e96860

	Navigate to kernel source

            https://github.com/sayeed99/android_kernel_asus_moorefield/commit/473163100d8c5a1bf89e3a7151f6c9016dcada0c


                         

