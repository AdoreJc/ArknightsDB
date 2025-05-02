# SimpleKVTable

**Namespace:** `Torappu.DB`


## Fields

- `Boolean m_inited`

- `Boolean m_isValid`


## Properties

- `Int32 Count`


## Methods

- `Void _InitWithData(Dictionary`2, IConverter)`

- `Void _InitDataFailed()`

- `Int32 get_Count()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DB
public class SimpleKVTable`2 : AbstractKVTable`2
{
	private Boolean m_inited; // 0x0
	protected Dictionary`2 m_dataMap; // 0x0
	private Boolean m_isValid; // 0x0
	private static DelegateBridge __Hotfix0_get_inited; // 0x0
	private static DelegateBridge __Hotfix0_Validate; // 0x0
	private static DelegateBridge __Hotfix0_get_data; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix1_Init; // 0x0
	private static DelegateBridge __Hotfix0_InitAsync; // 0x0
	private static DelegateBridge __Hotfix0__InitWithData; // 0x0
	private static DelegateBridge __Hotfix0__InitDataFailed; // 0x0
	private static DelegateBridge __Hotfix0_SerializeToString; // 0x0
	private static DelegateBridge __Hotfix0_GetDebugString; // 0x0
	private static DelegateBridge __Hotfix0_get_Count; // 0x0
	private static DelegateBridge __Hotfix0_GetEnumerator; // 0x0
	private static DelegateBridge __Hotfix0_TryGetValue; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0

	public override Boolean inited { get; }
	protected Dictionary`2 data { get; }
	public Int32 Count { get; }

	// RVA: 0x VA: 0x0
	public override Boolean get_inited() { }
	// RVA: 0x VA: 0x0
	public override Boolean Validate() { }
	// RVA: 0x VA: 0x0
	protected Dictionary`2 get_data() { }
	// RVA: 0x VA: 0x0
	public override Boolean Init(Stream reader, IConverter converter) { }
	// RVA: 0x VA: 0x0
	public override Boolean Init(TextAsset rawData, IConverter converter) { }
	// RVA: 0x VA: 0x0
	public override IAsyncLoadRequest InitAsync(IConverter converter) { }
	// RVA: 0x VA: 0x0
	private Void _InitWithData(Dictionary`2 data, IConverter converter) { }
	// RVA: 0x VA: 0x0
	private Void _InitDataFailed() { }
	// RVA: 0x VA: 0x0
	public override String SerializeToString(Boolean intended) { }
	// RVA: 0x VA: 0x0
	public override String GetDebugString() { }
	// RVA: 0x VA: 0x0
	public Int32 get_Count() { }
	// RVA: 0x VA: 0x0
	public override IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public override Boolean TryGetValue(String key, out TValue value) { }
	// RVA: 0x VA: 0x0
	protected virtual Void OnInit() { }
	// RVA: 0x VA: 0x0
	protected Void .ctor() { }
}
```