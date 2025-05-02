# NtpPacket

**Namespace:** `FlyingWormConsole3.LiteNetLib.Utils`


## Properties

- `NtpLeapIndicator LeapIndicator`

- `Int32 VersionNumber`

- `NtpMode Mode`

- `Int32 Stratum`

- `Int32 Poll`

- `Int32 Precision`

- `TimeSpan RootDelay`

- `TimeSpan RootDispersion`

- `UInt32 ReferenceId`

- `TimeSpan RoundTripTime`

- `TimeSpan CorrectionOffset`


## Methods

- `Void set_Bytes(Byte[])`

- `NtpLeapIndicator get_LeapIndicator()`

- `Int32 get_VersionNumber()`

- `Void set_VersionNumber(Int32)`

- `NtpMode get_Mode()`

- `Void set_Mode(NtpMode)`

- `Int32 get_Stratum()`

- `Int32 get_Poll()`

- `Int32 get_Precision()`

- `TimeSpan get_RootDelay()`

- `TimeSpan get_RootDispersion()`

- `UInt32 get_ReferenceId()`

- `Void set_TransmitTimestamp(Nullable`1)`

- `Void set_DestinationTimestamp(Nullable`1)`

- `TimeSpan get_RoundTripTime()`

- `TimeSpan get_CorrectionOffset()`

- `Void CheckTimestamps()`

- `Void SetDateTime64(Int32, Nullable`1)`

- `TimeSpan GetTimeSpan32(Int32)`

- `UInt64 GetUInt64BE(Int32)`

- `Void SetUInt64BE(Int32, UInt64)`

- `Int32 GetInt32BE(Int32)`

- `UInt32 GetUInt32BE(Int32)`


## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : FlyingWormConsole3.LiteNetLib.Utils
public class NtpPacket
{
	private static readonly DateTime Epoch; // 0x0
	private Byte[] <Bytes>k__BackingField; // 0x10
	private Nullable`1 <DestinationTimestamp>k__BackingField; // 0x18

	public Byte[] Bytes { get; set; }
	public NtpLeapIndicator LeapIndicator { get; }
	public Int32 VersionNumber { get; set; }
	public NtpMode Mode { get; set; }
	public Int32 Stratum { get; }
	public Int32 Poll { get; }
	public Int32 Precision { get; }
	public TimeSpan RootDelay { get; }
	public TimeSpan RootDispersion { get; }
	public UInt32 ReferenceId { get; }
	public Nullable`1 ReferenceTimestamp { get; }
	public Nullable`1 OriginTimestamp { get; }
	public Nullable`1 ReceiveTimestamp { get; }
	public Nullable`1 TransmitTimestamp { get; set; }
	public Nullable`1 DestinationTimestamp { get; set; }
	public TimeSpan RoundTripTime { get; }
	public TimeSpan CorrectionOffset { get; }

	// RVA: 0x410ab40 VA: 0x7596722b40
	public Byte[] get_Bytes() { }
	// RVA: 0x410ab48 VA: 0x7596722b48
	private Void set_Bytes(Byte[] value) { }
	// RVA: 0x410ab50 VA: 0x7596722b50
	public NtpLeapIndicator get_LeapIndicator() { }
	// RVA: 0x410ab7c VA: 0x7596722b7c
	public Int32 get_VersionNumber() { }
	// RVA: 0x410aba8 VA: 0x7596722ba8
	private Void set_VersionNumber(Int32 value) { }
	// RVA: 0x410abdc VA: 0x7596722bdc
	public NtpMode get_Mode() { }
	// RVA: 0x410ac08 VA: 0x7596722c08
	private Void set_Mode(NtpMode value) { }
	// RVA: 0x410ac3c VA: 0x7596722c3c
	public Int32 get_Stratum() { }
	// RVA: 0x410ac68 VA: 0x7596722c68
	public Int32 get_Poll() { }
	// RVA: 0x410ac94 VA: 0x7596722c94
	public Int32 get_Precision() { }
	// RVA: 0x410acc0 VA: 0x7596722cc0
	public TimeSpan get_RootDelay() { }
	// RVA: 0x410ad4c VA: 0x7596722d4c
	public TimeSpan get_RootDispersion() { }
	// RVA: 0x410ad54 VA: 0x7596722d54
	public UInt32 get_ReferenceId() { }
	// RVA: 0x410adfc VA: 0x7596722dfc
	public Nullable`1 get_ReferenceTimestamp() { }
	// RVA: 0x410af44 VA: 0x7596722f44
	public Nullable`1 get_OriginTimestamp() { }
	// RVA: 0x410af4c VA: 0x7596722f4c
	public Nullable`1 get_ReceiveTimestamp() { }
	// RVA: 0x410af54 VA: 0x7596722f54
	public Nullable`1 get_TransmitTimestamp() { }
	// RVA: 0x410af5c VA: 0x7596722f5c
	private Void set_TransmitTimestamp(Nullable`1 value) { }
	// RVA: 0x410b0d4 VA: 0x75967230d4
	public Nullable`1 get_DestinationTimestamp() { }
	// RVA: 0x410b0e0 VA: 0x75967230e0
	private Void set_DestinationTimestamp(Nullable`1 value) { }
	// RVA: 0x410b0e8 VA: 0x75967230e8
	public TimeSpan get_RoundTripTime() { }
	// RVA: 0x410b37c VA: 0x759672337c
	public TimeSpan get_CorrectionOffset() { }
	// RVA: 0x410b4f0 VA: 0x75967234f0
	public Void .ctor() { }
	// RVA: 0x410b5d4 VA: 0x75967235d4
	internal Void .ctor(Byte[] bytes) { }
	// RVA: 0x410b678 VA: 0x7596723678
	public static NtpPacket FromServerResponse(Byte[] bytes, DateTime destinationTimestamp) { }
	// RVA: 0x410b71c VA: 0x759672371c
	internal Void ValidateRequest() { }
	// RVA: 0x410b818 VA: 0x7596723818
	internal Void ValidateReply() { }
	// RVA: 0x410b248 VA: 0x7596723248
	private Void CheckTimestamps() { }
	// RVA: 0x410ae04 VA: 0x7596722e04
	private Nullable`1 GetDateTime64(Int32 offset) { }
	// RVA: 0x410af6c VA: 0x7596722f6c
	private Void SetDateTime64(Int32 offset, Nullable`1 value) { }
	// RVA: 0x410acc8 VA: 0x7596722cc8
	private TimeSpan GetTimeSpan32(Int32 offset) { }
	// RVA: 0x410b97c VA: 0x759672397c
	private UInt64 GetUInt64BE(Int32 offset) { }
	// RVA: 0x410ba1c VA: 0x7596723a1c
	private Void SetUInt64BE(Int32 offset, UInt64 value) { }
	// RVA: 0x410ba98 VA: 0x7596723a98
	private Int32 GetInt32BE(Int32 offset) { }
	// RVA: 0x410ad5c VA: 0x7596722d5c
	private UInt32 GetUInt32BE(Int32 offset) { }
	// RVA: 0x410bafc VA: 0x7596723afc
	private static UInt32 SwapEndianness(UInt32 x) { }
	// RVA: 0x410ba9c VA: 0x7596723a9c
	private static UInt64 SwapEndianness(UInt64 x) { }
	// RVA: 0x410bb04 VA: 0x7596723b04
	private static Void .cctor() { }
}
```