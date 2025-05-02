# NameCardV2MedalModuleView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `FriendNameCardMedalItem _medalItem`

- `GameObject _medalSettingIcon`

- `Button _openFriendMedalStateBtn`

- `UIPageListener m_pageListener`


## Properties

- `UIPageListener pageListener`


## Methods

- `UIPageListener get_pageListener()`

- `Void OpenMedalState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2MedalModuleView : NameCardV2BaseRemovableModuleView`1
{
	private FriendNameCardMedalItem _medalItem; // 0xb8
	private GameObject _medalSettingIcon; // 0xc0
	private Button _openFriendMedalStateBtn; // 0xc8
	private UIPageListener m_pageListener; // 0xd0
	private static DelegateBridge __Hotfix0_get_pageListener; // 0x0
	private static DelegateBridge __Hotfix0_OnModuleViewRendered; // 0x8
	private static DelegateBridge __Hotfix0_OpenMedalState; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected UIPageListener pageListener { get; }

	// RVA: 0x28e546c VA: 0x7594efd46c
	protected UIPageListener get_pageListener() { }
	// RVA: 0x28e5534 VA: 0x7594efd534
	public override Void OnModuleViewRendered(NameCardV2MedalModuleModel model) { }
	// RVA: 0x28e5724 VA: 0x7594efd724
	public Void OpenMedalState() { }
	// RVA: 0x28e57d4 VA: 0x7594efd7d4
	public Void .ctor() { }
}
```