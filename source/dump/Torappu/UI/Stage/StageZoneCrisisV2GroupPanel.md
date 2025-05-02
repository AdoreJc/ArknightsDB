# StageZoneCrisisV2GroupPanel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _unAvailPart`

- `GameObject _availPart`

- `StageZoneCrisisV2AvailPanel _availPanel`

- `Text _shopCoin`

- `AnimationWrapper _animWrapper`

- `Text _shopItemName`

- `Boolean m_isInited`


## Methods

- `Void Render(CrisisV2ZoneGroupViewModel)`

- `Void OpenAchivePage()`

- `Void OpenShopPage()`

- `Void OpenMapPage()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnValueChanged(ZoneGroupViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneCrisisV2GroupPanel : StageZoneGroupPanel
{
	private const String ANIM_ENTRY; // 0x0
	private GameObject _unAvailPart; // 0x60
	private GameObject _availPart; // 0x68
	private StageZoneCrisisV2AvailPanel _availPanel; // 0x70
	private Text _shopCoin; // 0x78
	private AnimationWrapper _animWrapper; // 0x80
	private Text _shopItemName; // 0x88
	public Boolean m_isInited; // 0x90
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OpenAchivePage; // 0x18
	private static DelegateBridge __Hotfix0_OpenShopPage; // 0x20
	private static DelegateBridge __Hotfix0_OpenMapPage; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2fb347c VA: 0x75955cb47c
	protected override Void OnEnter() { }
	// RVA: 0x2fb3518 VA: 0x75955cb518
	public override Void OnValueChanged(ZoneGroupViewProperty property) { }
	// RVA: 0x2fb378c VA: 0x75955cb78c
	public Void Render(CrisisV2ZoneGroupViewModel value) { }
	// RVA: 0x2fb390c VA: 0x75955cb90c
	public Void OpenAchivePage() { }
	// RVA: 0x2fb39a0 VA: 0x75955cb9a0
	public Void OpenShopPage() { }
	// RVA: 0x2fb3a34 VA: 0x75955cba34
	public Void OpenMapPage() { }
	// RVA: 0x2fb3ac8 VA: 0x75955cbac8
	public Void .ctor() { }
	// RVA: 0x2fb3b34 VA: 0x75955cbb34
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2fb3b38 VA: 0x75955cbb38
	private Void <>xLuaBaseProxy_OnValueChanged(ZoneGroupViewProperty P0) { }
}
```