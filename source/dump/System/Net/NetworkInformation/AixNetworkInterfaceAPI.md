# AixNetworkInterfaceAPI

**Namespace:** `System.Net.NetworkInformation`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.NetworkInformation
internal class AixNetworkInterfaceAPI : UnixNetworkInterfaceAPI
{


	// RVA: 0x6347910 VA: 0x759895f910
	public static extern Int32 socket(AixAddressFamily family, Int32 type, Int32 protocol) { }
	// RVA: 0x63479b0 VA: 0x759895f9b0
	public static extern Int32 close(Int32 fd) { }
	// RVA: 0x6347a28 VA: 0x759895fa28
	public static extern Int32 ioctl(Int32 fd, AixIoctlRequest request, ref Int32 arg) { }
	// RVA: 0x6347ac8 VA: 0x759895fac8
	public static extern Int32 ioctl(Int32 fd, AixIoctlRequest request, ref ifconf arg) { }
	// RVA: 0x6347b68 VA: 0x759895fb68
	public static extern Int32 ioctl(Int32 fd, AixIoctlRequest request, ref ifreq_flags arg) { }
	// RVA: 0x6347c08 VA: 0x759895fc08
	public static extern Int32 ioctl(Int32 fd, AixIoctlRequest request, ref ifreq_mtu arg) { }
	// RVA: 0x6347ca8 VA: 0x759895fca8
	private static Void ByteArrayCopy(Byte* dst, Byte* src, Int32 elements) { }
	// RVA: 0x6347cc4 VA: 0x759895fcc4
	public override NetworkInterface[] GetAllNetworkInterfaces() { }
	// RVA: 0x6348e14 VA: 0x7598960e14
	public Void .ctor() { }
}
```