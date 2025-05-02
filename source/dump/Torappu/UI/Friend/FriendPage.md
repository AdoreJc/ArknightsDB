# FriendPage

**Namespace:** `Torappu.UI.Friend`


## Fields

- `PrefabInstHolder _topMenuHolder`

- `Text _lvl`

- `Text _playerName`

- `Text _playerServer`

- `FriendStateControl _stateController`

- `FriendListStateBean _stateBean`

- `Image _bgImage`

- `Boolean m_isVisitBuildingUnlocked`


## Properties

- `Boolean isVisitBuildingUnlocked`


## Methods

- `Boolean get_isVisitBuildingUnlocked()`

- `Boolean CanInteractBuilding()`

- `IEnumerator _OpenState(Boolean)`

- `Void _OnInitTopMenu(GameObject)`

- `Void _SetBackgroundImg()`

- `Void VisitBuilding(String)`

- `Void <_OnInitTopMenu>b__19_0()`

- `AVGPageKey <>xLuaBaseProxy_get_avgPage()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnPageRouted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendPage : StateEnginePage, IBuildingPage
{
	private PrefabInstHolder _topMenuHolder; // 0xe8
	private Text _lvl; // 0xf0
	private Text _playerName; // 0xf8
	private Text _playerServer; // 0x100
	private FriendStateControl _stateController; // 0x108
	private FriendListStateBean _stateBean; // 0x110
	private Image _bgImage; // 0x118
	private Boolean m_isVisitBuildingUnlocked; // 0x120
	private static DelegateBridge __Hotfix0_get_avgPage; // 0x0
	private static DelegateBridge __Hotfix0_get_isVisitBuildingUnlocked; // 0x8
	private static DelegateBridge __Hotfix0_CanInteractBuilding; // 0x10
	private static DelegateBridge __Hotfix0_OnCreate; // 0x18
	private static DelegateBridge __Hotfix0_OnStart; // 0x20
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x28
	private static DelegateBridge __Hotfix0__OpenState; // 0x30
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x38
	private static DelegateBridge __Hotfix0__SetBackgroundImg; // 0x40
	private static DelegateBridge __Hotfix0_VisitBuilding; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public override AVGPageKey avgPage { get; }
	public Boolean isVisitBuildingUnlocked { get; }

	// RVA: 0x28ab4d0 VA: 0x7594ec34d0
	public override AVGPageKey get_avgPage() { }
	// RVA: 0x28ab538 VA: 0x7594ec3538
	public Boolean get_isVisitBuildingUnlocked() { }
	// RVA: 0x28ab5a0 VA: 0x7594ec35a0
	public Boolean CanInteractBuilding() { }
	// RVA: 0x28ab604 VA: 0x7594ec3604
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x28ab9b8 VA: 0x7594ec39b8
	protected override Void OnStart() { }
	// RVA: 0x28aba38 VA: 0x7594ec3a38
	protected override Void OnPageRouted() { }
	// RVA: 0x VA: 0x0
	private IEnumerator _OpenState(Boolean isFast) { }
	// RVA: 0x28abb28 VA: 0x7594ec3b28
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x28ab820 VA: 0x7594ec3820
	private Void _SetBackgroundImg() { }
	// RVA: 0x28abc70 VA: 0x7594ec3c70
	public Void VisitBuilding(String friendId) { }
	// RVA: 0x28abd28 VA: 0x7594ec3d28
	public Void .ctor() { }
	// RVA: 0x28abd98 VA: 0x7594ec3d98
	private Void <_OnInitTopMenu>b__19_0() { }
	// RVA: 0x28abda0 VA: 0x7594ec3da0
	private AVGPageKey <>xLuaBaseProxy_get_avgPage() { }
	// RVA: 0x28abda8 VA: 0x7594ec3da8
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x28abdb0 VA: 0x7594ec3db0
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x28abdb8 VA: 0x7594ec3db8
	private Void <>xLuaBaseProxy_OnPageRouted() { }
}
```