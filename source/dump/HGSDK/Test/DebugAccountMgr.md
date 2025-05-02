# DebugAccountMgr

**Namespace:** `HGSDK.Test`


## Fields

- `HGSDK m_sdk`


## Methods

- `Void Register(HGSDK)`

- `Void TraceGameInfo()`

- `Boolean DeleteAccount(Int32)`

- `Void _DoSave()`

- `Boolean ApplyAccount(Int32)`

- `Void _Init()`

- `Void <_Init>b__12_0(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.Test
public class DebugAccountMgr : Singleton`1
{
	private const String STORAGE_FILE; // 0x0
	private List`1 m_history; // 0x10
	private HGSDK m_sdk; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Register; // 0x8
	private static DelegateBridge __Hotfix0_TraceGameInfo; // 0x10
	private static DelegateBridge __Hotfix0_DeleteAccount; // 0x18
	private static DelegateBridge __Hotfix0__DoSave; // 0x20
	private static DelegateBridge __Hotfix0_ApplyAccount; // 0x28
	private static DelegateBridge __Hotfix0_get_accIter; // 0x30
	private static DelegateBridge __Hotfix0__Init; // 0x38

	public IEnumerable`1 accIter { get; }

	// RVA: 0x37534a4 VA: 0x7595d6b4a4
	private Void .ctor() { }
	// RVA: 0x3753534 VA: 0x7595d6b534
	public Void Register(HGSDK sdk) { }
	// RVA: 0x37535b8 VA: 0x7595d6b5b8
	public Void TraceGameInfo() { }
	// RVA: 0x3753f10 VA: 0x7595d6bf10
	public Boolean DeleteAccount(Int32 idx) { }
	// RVA: 0x3753cd4 VA: 0x7595d6bcd4
	private Void _DoSave() { }
	// RVA: 0x3754094 VA: 0x7595d6c094
	public Boolean ApplyAccount(Int32 idx) { }
	// RVA: 0x3754348 VA: 0x7595d6c348
	public IEnumerable`1 get_accIter() { }
	// RVA: 0x3753a6c VA: 0x7595d6ba6c
	private Void _Init() { }
	// RVA: 0x3754438 VA: 0x7595d6c438
	private Void <_Init>b__12_0(String content) { }
}
```