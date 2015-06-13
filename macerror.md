Anonymous UUID:       035B035B-B882-B427-C3BE-BC8C248E31E5

Sat Jun 13 17:31:08 2015
panic(cpu 0 caller 0xffffff8001e33bd4): "Spinlock acquisition timed out: lock=0xffffff80024ca528, lock owner thread=0xffffff8016c3b450, current_thread: 0xffffff80147bab20, lock owner active on CPU 0x3, current owner: 0xffffff8016c3b450"@/SourceCache/xnu/xnu-2422.110.17/osfmk/i386/locks_i386.c:365
Backtrace (CPU 0), Frame : Return Address
0xffffff80e4ac8d00 : 0xffffff8001e22f79 
0xffffff80e4ac8d80 : 0xffffff8001e33bd4 
0xffffff80e4ac8dc0 : 0xffffff8001e337a5 
0xffffff80e4ac8e10 : 0xffffff8001e3367b 
0xffffff80e4ac8e40 : 0xffffff8001e4c130 
0xffffff80e4ac8f10 : 0xffffff8001ecf779 
0xffffff80e4ac8f50 : 0xffffff8001ee22c6 
0xffffff80e4ac8f80 : 0xffffff8001edb80f 
0xffffff80e4ac8fd0 : 0xffffff8001ef3909 
0xffffff810c413f10 : 0xffffff7f83c06023 
0xffffff810c413f30 : 0xffffff80022af292 
0xffffff810c413f80 : 0xffffff80022af367 
0xffffff810c413fb0 : 0xffffff8001ed7417 
      Kernel Extensions in backtrace:
         com.apple.driver.AppleAHCIPort(3.0.5)[7F56F309-28C2-342A-82C0-3908C164EBCC]@0xffffff7f83bfc000->0xffffff7f83c15fff
            dependency: com.apple.iokit.IOAHCIFamily(2.6.5)[AB2D7D6A-B59B-3039-AE08-CBCC38208911]@0xffffff7f82fd6000
            dependency: com.apple.iokit.IOPCIFamily(2.9)[4662B11D-2ECA-315D-875C-618C97CDAB2A]@0xffffff7f824be000

BSD process name corresponding to current thread: kernel_task

Mac OS version:
13E28

Kernel version:
Darwin Kernel Version 13.3.0: Tue Jun  3 21:27:35 PDT 2014; root:xnu-2422.110.17~1/RELEASE_X86_64
Kernel UUID: BBFADD17-672B-35A2-9B7F-E4B12213E4B8
Kernel slide:     0x0000000001c00000
Kernel text base: 0xffffff8001e00000
System model name: MacBookPro8,2 (Mac-94245A3940C91C80)

System uptime in nanoseconds: 481431163814
last loaded kext at 404725715736: com.apple.driver.AppleIntelMCEReporter	104 (addr 0xffffff7f846e4000, size 49152)
last unloaded kext at 362464468768: com.apple.driver.AppleUSBUHCI	656.4.1 (addr 0xffffff7f82b1f000, size 65536)
loaded kexts:
com.wavtap.driver.WavTap	0.4.0
com.apple.driver.AppleIntelMCEReporter	104
com.apple.driver.AppleHWSensor	1.9.5d0
com.apple.driver.AGPM	100.14.28
com.apple.filesystems.autofs	3.0
com.apple.iokit.IOBluetoothSerialManager	4.2.6f1
com.apple.driver.AppleMikeyHIDDriver	124
com.apple.driver.AppleMikeyDriver	2.6.3f4
com.apple.driver.AppleHDA	2.6.3f4
com.apple.driver.AudioAUUC	1.60
com.apple.driver.AppleUpstreamUserClient	3.5.13
com.apple.kext.AMDFramebuffer	1.2.4
com.apple.iokit.IOUserEthernet	1.0.0d1
com.apple.driver.AppleIntelHD3000Graphics	8.2.4
com.apple.AMDRadeonX3000	1.2.4
com.apple.Dont_Steal_Mac_OS_X	7.0.0
com.apple.driver.AppleHWAccess	1
com.apple.driver.AppleSMCLMU	2.0.4d1
com.apple.iokit.BroadcomBluetoothHostControllerUSBTransport	4.2.6f1
com.apple.kext.AMD6000Controller	1.2.4
com.apple.driver.ACPI_SMC_PlatformPlugin	1.0.0
com.apple.driver.AppleLPC	1.7.0
com.apple.driver.AppleIntelSNBGraphicsFB	8.2.4
com.apple.driver.AppleMuxControl	3.6.22
com.apple.driver.AppleMCCSControl	1.2.5
com.apple.driver.SMCMotionSensor	3.0.4d1
com.apple.driver.AppleSMCPDRC	1.0.0
com.apple.driver.AppleThunderboltIP	1.1.2
com.apple.driver.AppleUSBTCButtons	240.2
com.apple.driver.AppleUSBTCKeyboard	240.2
com.apple.driver.AppleIRController	325.7
com.apple.AppleFSCompression.AppleFSCompressionTypeDataless	1.0.0d1
com.apple.AppleFSCompression.AppleFSCompressionTypeLZVN	1.0.0d1
com.apple.AppleFSCompression.AppleFSCompressionTypeZlib	1.0.0d1
com.apple.BootCache	35
com.apple.iokit.SCSITaskUserClient	3.6.6
com.apple.driver.XsanFilter	404
com.apple.iokit.IOAHCIBlockStorage	2.6.0
com.apple.driver.AppleUSBHub	683.4.0
com.apple.driver.AirPort.Brcm4331	700.20.22
com.apple.driver.AppleSDXC	1.5.2
com.apple.iokit.AppleBCM5701Ethernet	3.8.1b2
com.apple.driver.AppleFWOHCI	5.0.2
com.apple.driver.AppleAHCIPort	3.0.5
com.apple.driver.AppleUSBEHCI	660.4.0
com.apple.driver.AppleSmartBatteryManager	161.0.0
com.apple.driver.AppleACPIButtons	2.0
com.apple.driver.AppleRTC	2.0
com.apple.driver.AppleHPET	1.8
com.apple.driver.AppleSMBIOS	2.1
com.apple.driver.AppleACPIEC	2.0
com.apple.driver.AppleAPIC	1.7
com.apple.driver.AppleIntelCPUPowerManagementClient	217.92.1
com.apple.nke.applicationfirewall	153
com.apple.security.quarantine	3
com.apple.driver.AppleIntelCPUPowerManagement	217.92.1
com.apple.kext.triggers	1.0
com.apple.iokit.IOSerialFamily	10.0.7
com.apple.driver.DspFuncLib	2.6.3f4
com.apple.vecLib.kext	1.0.0
com.apple.iokit.IOAudioFamily	1.9.7fc2
com.apple.kext.OSvKernDSPLib	1.14
com.apple.iokit.IOSurface	91.1
com.apple.iokit.IOBluetoothFamily	4.2.6f1
com.apple.iokit.IOAcceleratorFamily	98.22
com.apple.iokit.IOBluetoothHostControllerUSBTransport	4.2.6f1
com.apple.iokit.IOFireWireIP	2.2.6
com.apple.kext.AMDSupport	1.2.4
com.apple.AppleGraphicsDeviceControl	3.6.22
com.apple.driver.IOPlatformPluginLegacy	1.0.0
com.apple.driver.AppleSMBusPCI	1.0.12d1
com.apple.driver.AppleGraphicsControl	3.6.22
com.apple.driver.AppleBacklightExpert	1.0.4
com.apple.iokit.IONDRVSupport	2.4.1
com.apple.driver.AppleSMBusController	1.0.12d1
com.apple.driver.AppleSMC	3.1.8
com.apple.driver.IOPlatformPluginFamily	5.7.1d6
com.apple.driver.AppleHDAController	2.6.3f4
com.apple.iokit.IOGraphicsFamily	2.4.1
com.apple.iokit.IOHDAFamily	2.6.3f4
com.apple.driver.AppleThunderboltDPInAdapter	3.1.7
com.apple.driver.AppleThunderboltDPAdapterFamily	3.1.7
com.apple.driver.AppleThunderboltPCIDownAdapter	1.4.5
com.apple.driver.AppleUSBMultitouch	240.9
com.apple.iokit.IOUSBHIDDriver	660.4.0
com.apple.driver.AppleUSBMergeNub	650.4.0
com.apple.driver.AppleUSBComposite	656.4.1
com.apple.iokit.IOSCSIMultimediaCommandsDevice	3.6.6
com.apple.iokit.IOBDStorageFamily	1.7
com.apple.iokit.IODVDStorageFamily	1.7.1
com.apple.iokit.IOCDStorageFamily	1.7.1
com.apple.iokit.IOAHCISerialATAPI	2.6.1
com.apple.iokit.IOSCSIArchitectureModelFamily	3.6.6
com.apple.driver.AppleThunderboltNHI	2.0.1
com.apple.iokit.IOThunderboltFamily	3.3.1
com.apple.iokit.IOUSBUserClient	660.4.2
com.apple.iokit.IO80211Family	640.36
com.apple.iokit.IOEthernetAVBController	1.0.3b4
com.apple.driver.mDNSOffloadUserClient	1.0.1b5
com.apple.iokit.IONetworkingFamily	3.2
com.apple.iokit.IOFireWireFamily	4.5.5
com.apple.iokit.IOAHCIFamily	2.6.5
com.apple.iokit.IOUSBFamily	683.4.0
com.apple.driver.AppleEFINVRAM	2.0
com.apple.iokit.IOHIDFamily	2.0.0
com.apple.driver.AppleEFIRuntime	2.0
com.apple.iokit.IOSMBusFamily	1.1
com.apple.security.sandbox	278.11.1
com.apple.kext.AppleMatch	1.0.0d1
com.apple.security.TMSafetyNet	7
com.apple.driver.AppleKeyStore	2
com.apple.driver.DiskImages	371.1
com.apple.iokit.IOStorageFamily	1.9
com.apple.iokit.IOReportFamily	23
com.apple.driver.AppleFDEKeyStore	28.30
com.apple.driver.AppleACPIPlatform	2.0
com.apple.iokit.IOPCIFamily	2.9
com.apple.iokit.IOACPIFamily	1.4
com.apple.kec.pthread	1
com.apple.kec.corecrypto	1.0

