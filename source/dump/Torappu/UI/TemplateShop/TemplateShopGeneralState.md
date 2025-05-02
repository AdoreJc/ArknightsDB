# TemplateShopGeneralState

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `PrefabInstHolder _topMenuHolder`

- `TemplateShopCommonLeftViewHolder _leftPart`

- `TemplateShopCommonRightViewHolder _rightParts`

- `TemplateShopNormalDetailStateBean m_stateBean`


## Methods

- `Void OnClick()`

- `Void OnClickComplex()`

- `Void RefreshReplicate()`

- `Void <OnEnter>b__5_0(GameObject)`

- `Void <OnClick>b__6_0()`

- `Void <OnClickComplex>b__7_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopGeneralState : PopupFloatState
{
	private PrefabInstHolder _topMenuHolder; // 0x70
	private TemplateShopCommonLeftViewHolder _leftPart; // 0x78
	private TemplateShopCommonRightViewHolder _rightParts; // 0x80
	private TemplateShopNormalDetailStateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0_OnClickComplex; // 0x18
	private static DelegateBridge __Hotfix0_RefreshReplicate; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2353db4 VA: 0x759496bdb4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2353e1c VA: 0x759496be1c
	protected override Void OnEnter() { }
	// RVA: 0x2354418 VA: 0x759496c418
	public Void OnClick() { }
	// RVA: 0x23544e0 VA: 0x759496c4e0
	public Void OnClickComplex() { }
	// RVA: 0x23542a8 VA: 0x759496c2a8
	public Void RefreshReplicate() { }
	// RVA: 0x2354768 VA: 0x759496c768
	public Void .ctor() { }
	// RVA: 0x2354814 VA: 0x759496c814
	private Void <OnEnter>b__5_0(GameObject gameObj) { }
	// RVA: 0x2354904 VA: 0x759496c904
	private Void <OnClick>b__6_0() { }
	// RVA: 0x2354914 VA: 0x759496c914
	private Void <OnClickComplex>b__7_0() { }
	// RVA: 0x2354924 VA: 0x759496c924
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```