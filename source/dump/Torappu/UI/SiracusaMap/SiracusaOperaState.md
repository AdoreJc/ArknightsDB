# SiracusaOperaState

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SiracusaOperaStateBean m_stateBean`

- `SiracusaOperaFrameHolder _holder`

- `SiracusaOperaFavorView _favorView`


## Methods

- `Void OnSelectFrame(Int32)`

- `Void <RegisterToDataListener>b__6_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaOperaState : PopupFadeState
{
	private SiracusaOperaStateBean m_stateBean; // 0x70
	private SiracusaOperaFrameHolder _holder; // 0x78
	private SiracusaOperaFavorView _favorView; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_OnSelectFrame; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x23fa0b4 VA: 0x7594a120b4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x23fa11c VA: 0x7594a1211c
	protected override Void OnEnter() { }
	// RVA: 0x23fa52c VA: 0x7594a1252c
	protected override Void OnResume() { }
	// RVA: 0x23fa614 VA: 0x7594a12614
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x23fa78c VA: 0x7594a1278c
	public Void OnSelectFrame(Int32 index) { }
	// RVA: 0x23fa9bc VA: 0x7594a129bc
	public Void .ctor() { }
	// RVA: 0x23faa68 VA: 0x7594a12a68
	private Void <RegisterToDataListener>b__6_0(IStateBean stateBean) { }
	// RVA: 0x23fab2c VA: 0x7594a12b2c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x23fab34 VA: 0x7594a12b34
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x23fab3c VA: 0x7594a12b3c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```