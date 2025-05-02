# ConstTable

**Namespace:** `Torappu.DB`


## Fields

- `Boolean m_inited`

- `TValue m_data`

- `Boolean m_isValid`


## Properties

- `TValue instData`


## Methods

- `TValue get_instData()`

- `Void _InitWithData(TValue, IConverter)`

- `Void _InitDataFailed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DB
public class ConstTable`2 : SingletonAbstractTable`1
{
	private Boolean m_inited; // 0x0
	private TValue m_data; // 0x0
	private Boolean m_isValid; // 0x0
	private static DelegateBridge __Hotfix0_get_inited; // 0x0
	private static DelegateBridge __Hotfix0_get_data; // 0x0
	private static DelegateBridge __Hotfix0_get_instData; // 0x0
	private static DelegateBridge __Hotfix0_Validate; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix1_Init; // 0x0
	private static DelegateBridge __Hotfix0_InitAsync; // 0x0
	private static DelegateBridge __Hotfix0__InitWithData; // 0x0
	private static DelegateBridge __Hotfix0__InitDataFailed; // 0x0
	private static DelegateBridge __Hotfix0_SerializeToString; // 0x0
	private static DelegateBridge __Hotfix0_GetDebugString; // 0x0
	private static DelegateBridge __Hotfix0_GetDataType; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0

	public override Boolean inited { get; }
	public static TValue data { get; }
	public TValue instData { get; }

	// RVA: 0x VA: 0x0
	public override Boolean get_inited() { }
	// RVA: 0x VA: 0x0
	public static TValue get_data() { }
	// RVA: 0x VA: 0x0
	public TValue get_instData() { }
	// RVA: 0x VA: 0x0
	public override Boolean Validate() { }
	// RVA: 0x VA: 0x0
	public override Boolean Init(Stream stream, IConverter converter) { }
	// RVA: 0x VA: 0x0
	public override Boolean Init(TextAsset rawData, IConverter converter) { }
	// RVA: 0x VA: 0x0
	public override IAsyncLoadRequest InitAsync(IConverter converter) { }
	// RVA: 0x VA: 0x0
	private Void _InitWithData(TValue data, IConverter converter) { }
	// RVA: 0x VA: 0x0
	private Void _InitDataFailed() { }
	// RVA: 0x VA: 0x0
	public override String SerializeToString(Boolean intended) { }
	// RVA: 0x VA: 0x0
	public override String GetDebugString() { }
	// RVA: 0x VA: 0x0
	public override Type GetDataType() { }
	// RVA: 0x VA: 0x0
	protected virtual Void OnInit() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```