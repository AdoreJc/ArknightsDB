# FriendAssistView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Transform _assistTabContainer`

- `FriendAssistItemFloatPanel _assistFloatPanel`

- `Text _descUp`

- `Text _descDown`

- `FriendAssistSelectEvent _onApplySelect`

- `FriendAssistSelectEvent _onFloatSelect`

- `Boolean m_isInited`

- `GameObject m_cachedItemObject`


## Methods

- `Void _InitIfNot()`

- `Void _ShowView(FriendListViewModel)`

- `Void _RenderFloatPanel(FriendListViewModel)`

- `Void _OnTabItemClick(Int32, String, GameObject, ItemType)`

- `Void _OnPanelItemClick(Int32, String, ItemType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendAssistView : DataBinder`1
{
	private const Int32 MAX_ASSIST_TAB_COUNT; // 0x0
	private Transform _assistTabContainer; // 0x20
	private FriendAssistItemFloatPanel _assistFloatPanel; // 0x28
	private Text _descUp; // 0x30
	private Text _descDown; // 0x38
	private FriendAssistSelectEvent _onApplySelect; // 0x40
	private FriendAssistSelectEvent _onFloatSelect; // 0x48
	private List`1 m_friendAssistTabs; // 0x50
	private Boolean m_isInited; // 0x58
	private GameObject m_cachedItemObject; // 0x60
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__ShowView; // 0x10
	private static DelegateBridge __Hotfix0__RenderFloatPanel; // 0x18
	private static DelegateBridge __Hotfix0__OnTabItemClick; // 0x20
	private static DelegateBridge __Hotfix0__OnPanelItemClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x28cafa0 VA: 0x7594ee2fa0
	public override Void OnValueChanged(FriendListProperty property) { }
	// RVA: 0x28cb080 VA: 0x7594ee3080
	private Void _InitIfNot() { }
	// RVA: 0x28cb5cc VA: 0x7594ee35cc
	private Void _ShowView(FriendListViewModel viewModel) { }
	// RVA: 0x28cb3a0 VA: 0x7594ee33a0
	private Void _RenderFloatPanel(FriendListViewModel viewModel) { }
	// RVA: 0x28cb858 VA: 0x7594ee3858
	private Void _OnTabItemClick(Int32 index, String id, GameObject item, ItemType itemType) { }
	// RVA: 0x28cb944 VA: 0x7594ee3944
	private Void _OnPanelItemClick(Int32 index, String id, ItemType itemType) { }
	// RVA: 0x28cba18 VA: 0x7594ee3a18
	public Void .ctor() { }
}
```