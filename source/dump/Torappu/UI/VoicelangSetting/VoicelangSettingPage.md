# VoicelangSettingPage

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `LoopScrollRect _scrollRectToStop`


## Methods

- `Void EventOnFilterClick()`

- `Void ReturnPage()`

- `Void <>xLuaBaseProxy_OnStart()`

- `Boolean <>xLuaBaseProxy_CustomSetActive(Boolean)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangSettingPage : StateEnginePage, IHotfixable
{
	private LoopScrollRect _scrollRectToStop; // 0xe8
	private static DelegateBridge __Hotfix0_OnStart; // 0x0
	private static DelegateBridge __Hotfix0_CustomSetActive; // 0x8
	private static DelegateBridge __Hotfix0_EventOnFilterClick; // 0x10
	private static DelegateBridge __Hotfix0_ReturnPage; // 0x18
	private static DelegateBridge __Hotfix0_OnCreate; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x229cae0 VA: 0x75948b4ae0
	protected override Void OnStart() { }
	// RVA: 0x229cb4c VA: 0x75948b4b4c
	public override Boolean CustomSetActive(Boolean active) { }
	// RVA: 0x229cc80 VA: 0x75948b4c80
	public Void EventOnFilterClick() { }
	// RVA: 0x229cd50 VA: 0x75948b4d50
	public Void ReturnPage() { }
	// RVA: 0x229ce84 VA: 0x75948b4e84
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x229cf08 VA: 0x75948b4f08
	public Void .ctor() { }
	// RVA: 0x229cf78 VA: 0x75948b4f78
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x229cf80 VA: 0x75948b4f80
	private Boolean <>xLuaBaseProxy_CustomSetActive(Boolean P0) { }
	// RVA: 0x229cf8c VA: 0x75948b4f8c
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```