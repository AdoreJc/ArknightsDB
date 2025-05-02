# NetMsg

**Namespace:** `Torappu.SocketNetwork`


## Fields

- `NetMsgID <id>k__BackingField`

- `ByteArray <data>k__BackingField`


## Properties

- `NetMsgID id`

- `ByteArray data`


## Methods

- `NetMsgID get_id()`

- `Void set_id(NetMsgID)`

- `ByteArray get_data()`

- `Void set_data(ByteArray)`

- `Void Reset(NetMsgID)`

- `T ToProtocol()`

- `Void Fill(NetMsgID, Byte[], Int32, Int32)`

- `Void OnAllocate()`

- `Void OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SocketNetwork
public class NetMsg : IReusable
{
	private static Object s_rsync_obj; // 0x0
	private static ObjectPool`1 s_pool; // 0x8
	public static Int32 DEFAULT_MSG_DATA_CAPACITY; // 0x10
	public const Int32 LEN_SIZE; // 0x0
	public const Int32 ID_SIZE; // 0x0
	public const Int32 HEAD_SIZE; // 0x0
	private NetMsgID <id>k__BackingField; // 0x10
	private ByteArray <data>k__BackingField; // 0x18

	public static Int32 allAllocatedCnt { get; }
	public static Int32 unusedCnt { get; }
	public NetMsgID id { get; set; }
	public ByteArray data { get; set; }

	// RVA: 0x356f64c VA: 0x7595b8764c
	public static NetMsg Create() { }
	// RVA: 0x356f904 VA: 0x7595b87904
	public static NetMsg Create(NetMsgID pid) { }
	// RVA: 0x356f9a0 VA: 0x7595b879a0
	public static NetMsg Recycle(NetMsg msg) { }
	// RVA: 0x356fb0c VA: 0x7595b87b0c
	public static Void ClearPool() { }
	// RVA: 0x356fb94 VA: 0x7595b87b94
	public static Int32 get_allAllocatedCnt() { }
	// RVA: 0x356fc3c VA: 0x7595b87c3c
	public static Int32 get_unusedCnt() { }
	// RVA: 0x356fce4 VA: 0x7595b87ce4
	public NetMsgID get_id() { }
	// RVA: 0x356fcec VA: 0x7595b87cec
	private Void set_id(NetMsgID value) { }
	// RVA: 0x356fcf4 VA: 0x7595b87cf4
	public ByteArray get_data() { }
	// RVA: 0x356fcfc VA: 0x7595b87cfc
	private Void set_data(ByteArray value) { }
	// RVA: 0x356fd04 VA: 0x7595b87d04
	private Void .ctor() { }
	// RVA: 0x356f97c VA: 0x7595b8797c
	public Void Reset(NetMsgID protocolID) { }
	// RVA: 0x VA: 0x0
	public T ToProtocol() { }
	// RVA: 0x356fdb8 VA: 0x7595b87db8
	public Void Fill(NetMsgID pid, Byte[] data, Int32 offset, Int32 len) { }
	// RVA: 0x356fe10 VA: 0x7595b87e10
	public Void OnAllocate() { }
	// RVA: 0x356fe14 VA: 0x7595b87e14
	public Void OnRecycle() { }
	// RVA: 0x356fe40 VA: 0x7595b87e40
	private static Void .cctor() { }
}
```