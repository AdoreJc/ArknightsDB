# TssInfoPublisher

**Namespace:** `ACE`


## Methods

- `Void registTssInfoReceiver(TssInfoReceiver)`

- `Void broadcastInfo(Int32, String)`

- `Void recvDataThread()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : ACE
public class TssInfoPublisher
{
	public const Int32 TSS_INFO_TYPE_DETECT_RESULT; // 0x0
	public const Int32 TSS_INFO_TYPE_HEARTBEAT; // 0x0
	private static TssInfoPublisher mInstance; // 0x0
	private static readonly Object mSingletonLock; // 0x8
	private readonly Object padlockReceiver; // 0x10
	private static List`1 mReceivers; // 0x10
	private static Thread mTssInfoPublisherThread; // 0x18
	private static Boolean mTssInfoPublisherThreadStarted; // 0x20


	// RVA: 0x66ba9dc VA: 0x7598cd29dc
	private Void .ctor() { }
	// RVA: 0x66baa50 VA: 0x7598cd2a50
	public static TssInfoPublisher getInstance() { }
	// RVA: 0x66bac04 VA: 0x7598cd2c04
	public Void registTssInfoReceiver(TssInfoReceiver receiver) { }
	// RVA: 0x66baf9c VA: 0x7598cd2f9c
	private Void broadcastInfo(Int32 id, String info) { }
	// RVA: 0x66bb238 VA: 0x7598cd3238
	private Void recvDataThread() { }
	// RVA: 0x66bb4f4 VA: 0x7598cd34f4
	private static Int32 openPipe() { }
	// RVA: 0x66bb754 VA: 0x7598cd3754
	private static Void closePipe() { }
	// RVA: 0x66bb5b4 VA: 0x7598cd35b4
	private static String recvPipe() { }
	// RVA: 0x66bb794 VA: 0x7598cd3794
	private static Void .cctor() { }
}
```