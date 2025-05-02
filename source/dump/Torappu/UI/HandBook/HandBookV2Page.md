# HandBookV2Page

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `HandBookV2MapPosDB _handbookPosDBComponent`

- `HandBookV2ForceMapDB _handbookForceMapDBComponent`

- `HandBookJumpParam <jumpParam>k__BackingField`


## Properties

- `HandBookJumpParam jumpParam`


## Methods

- `HandBookJumpParam get_jumpParam()`

- `Void set_jumpParam(HandBookJumpParam)`

- `HandBookV2MapPosData GetData()`

- `HandBookV2ForceMapData GetForceMapData()`

- `Void _ReturnPage()`

- `Void SetTopMenuActive(Boolean)`

- `IEnumerator <>n__0()`

- `Void <OnCreate>b__12_0(GameObject)`

- `Void <OnCreate>b__12_1()`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2Page : StateEnginePage
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0xe8
	private HandBookV2MapPosDB _handbookPosDBComponent; // 0xf0
	private HandBookV2ForceMapDB _handbookForceMapDBComponent; // 0xf8
	private HandBookJumpParam <jumpParam>k__BackingField; // 0x100
	private static DelegateBridge __Hotfix0_get_jumpParam; // 0x0
	private static DelegateBridge __Hotfix0_set_jumpParam; // 0x8
	private static DelegateBridge __Hotfix0_GetData; // 0x10
	private static DelegateBridge __Hotfix0_GetForceMapData; // 0x18
	private static DelegateBridge __Hotfix0__ReturnPage; // 0x20
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x28
	private static DelegateBridge __Hotfix0_SetTopMenuActive; // 0x30
	private static DelegateBridge __Hotfix0_OnCreate; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public HandBookJumpParam jumpParam { get; set; }

	// RVA: 0x2ec52c0 VA: 0x75954dd2c0
	public HandBookJumpParam get_jumpParam() { }
	// RVA: 0x2ec5328 VA: 0x75954dd328
	public Void set_jumpParam(HandBookJumpParam value) { }
	// RVA: 0x2ec53ac VA: 0x75954dd3ac
	public HandBookV2MapPosData GetData() { }
	// RVA: 0x2ec5434 VA: 0x75954dd434
	public HandBookV2ForceMapData GetForceMapData() { }
	// RVA: 0x2ec54bc VA: 0x75954dd4bc
	private Void _ReturnPage() { }
	// RVA: 0x2ec5584 VA: 0x75954dd584
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2ec5630 VA: 0x75954dd630
	public Void SetTopMenuActive(Boolean activeFlag) { }
	// RVA: 0x2ec56c4 VA: 0x75954dd6c4
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2ec5820 VA: 0x75954dd820
	public Void .ctor() { }
	// RVA: 0x2ec5890 VA: 0x75954dd890
	private IEnumerator <>n__0() { }
	// RVA: 0x2ec5898 VA: 0x75954dd898
	private Void <OnCreate>b__12_0(GameObject inst) { }
	// RVA: 0x2ec5950 VA: 0x75954dd950
	private Void <OnCreate>b__12_1() { }
	// RVA: 0x2ec5954 VA: 0x75954dd954
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
	// RVA: 0x2ec595c VA: 0x75954dd95c
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```