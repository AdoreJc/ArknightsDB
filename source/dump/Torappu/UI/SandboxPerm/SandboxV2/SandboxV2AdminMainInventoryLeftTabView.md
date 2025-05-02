# SandboxV2AdminMainInventoryLeftTabView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainInventoryPanelModelProperty m_cachedProp`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainInventoryLeftTabView : SandboxV2AdminMainTypeSelectViewBase`2
{
	private SandboxV2AdminMainInventoryLeftTabDefine[] _typeDefine; // 0x50
	private SandboxV2AdminMainInventoryPanelModelProperty m_cachedProp; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_GetDefinedTypeList; // 0x8
	private static DelegateBridge __Hotfix0_OnTypeSelectChanged; // 0x10
	private static DelegateBridge __Hotfix0_CheckIfShowRacingInfoBtn; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x24d4a50 VA: 0x7594aeca50
	public override Void OnValueChanged(SandboxV2AdminMainInventoryPanelModelProperty property) { }
	// RVA: 0x24d4b9c VA: 0x7594aecb9c
	protected override IList`1 GetDefinedTypeList() { }
	// RVA: 0x24d4c04 VA: 0x7594aecc04
	protected override Void OnTypeSelectChanged(SandboxV2AdminMainInventoryItemShowType selectType) { }
	// RVA: 0x24d4cec VA: 0x7594aeccec
	protected override Boolean CheckIfShowRacingInfoBtn() { }
	// RVA: 0x24d4dcc VA: 0x7594aecdcc
	public Void .ctor() { }
}
```