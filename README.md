Device configuration for Sony Xperia XZ Premium (maple)
========================================================

Description
-----------

This repository is for EvolutionX_elle on Sony Xperia XZ Premium (maple).

Local Manifest

        <?xml version="1.0" encoding="UTF-8"?>
        <manifest>
                <!-- Device trees -->
                <project name="Alcatraz323/android_device_sony_yoshino-common" path="device/sony/yoshino-common" remote="github" revision="elle" />
                <project name="Alcatraz323/android_device_sony_maple" path="device/sony/maple_dsds" remote="github" revision="elle" />
                <!-- Blobs -->
                <project name="Alcatraz323/android_vendor_sony_maple" path="vendor/sony/maple_dsds" remote="github" revision="elle" />
                <!-- Kernel -->
                <project name="Alcatraz323/android_kernel_sony_msm8998-EAS" path="kernel/sony/msm8998" remote="github" revision="elle" />
                <!-- PowerHAL for yoshino -->
                <project name="Alcatraz323/qcom_8998_powerHAL" path="vendor/qcom/opensource/powerHAL" remote="github" revision="elle" />
        </manifest>