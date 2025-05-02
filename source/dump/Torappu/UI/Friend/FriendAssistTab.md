# FriendAssistTab

**Namespace:** `Torappu.UI.Friend`


## Fields

- `GameObject _specMaxPart`

- `Text _levelText`

- `UIAtlasImage _characterIcon`

- `Image _eliteImage`

- `Image _potentialImage`

- `ThreeStateToggle _backStage`

- `GameObject _limitPart`

- `Text _limitText`

- `FriendAssistSkillItem _selectedSkillIcon`

- `FriendAssistEquipItem _selectedEquipIcon`

- `GameObject _reselectIcon`

- `UIScaler _scaler`

- `FriendAssistCharData m_cachedAssistCharData`

- `Int32 m_index`


## Properties

- `FriendAssistCharData assistCharData`


## Methods

- `FriendAssistCharData get_assistCharData()`

- `Void OnTabClick()`

- `Void SetLock()`

- `Void ResetData(Int32)`

- `Void ApplyData(FriendAssistCharData)`

- `Void ApplyData(SharedCharData, Boolean)`

- `Void _InitData()`

- `Void _OnClick(String, ItemType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendAssistTab : MonoBehaviour, IHotfixable
{
	private GameObject _specMaxPart; // 0x18
	private Text _levelText; // 0x20
	private UIAtlasImage _characterIcon; // 0x28
	private Image _eliteImage; // 0x30
	private Image _potentialImage; // 0x38
	private ThreeStateToggle _backStage; // 0x40
	private GameObject _limitPart; // 0x48
	private Text _limitText; // 0x50
	private FriendAssistSkillItem _selectedSkillIcon; // 0x58
	private FriendAssistEquipItem _selectedEquipIcon; // 0x60
	private GameObject _reselectIcon; // 0x68
	private UIScaler _scaler; // 0x70
	public Action`4 onItemClicked; // 0x78
	public Action`1 onTabClicked; // 0x80
	private FriendAssistCharData m_cachedAssistCharData; // 0x88
	private Int32 m_index; // 0x90
	private static DelegateBridge __Hotfix0_get_assistCharData; // 0x0
	private static DelegateBridge __Hotfix0_OnTabClick; // 0x8
	private static DelegateBridge __Hotfix0_SetLock; // 0x10
	private static DelegateBridge __Hotfix0_ResetData; // 0x18
	private static DelegateBridge __Hotfix0_ApplyData; // 0x20
	private static DelegateBridge __Hotfix1_ApplyData; // 0x28
	private static DelegateBridge __Hotfix0__InitData; // 0x30
	private static DelegateBridge __Hotfix0__OnClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public FriendAssistCharData assistCharData { get; }

	// RVA: 0x28ca244 VA: 0x7594ee2244
	public FriendAssistCharData get_assistCharData() { }
	// RVA: 0x28ca2ac VA: 0x7594ee22ac
	public Void OnTabClick() { }
	// RVA: 0x28ca334 VA: 0x7594ee2334
	public Void SetLock() { }
	// RVA: 0x28ca548 VA: 0x7594ee2548
	public Void ResetData(Int32 index) { }
	// RVA: 0x28ca5e0 VA: 0x7594ee25e0
	public Void ApplyData(FriendAssistCharData assistCharData) { }
	// RVA: 0x28caa80 VA: 0x7594ee2a80
	public Void ApplyData(SharedCharData cardData, Boolean isSkillLimited) { }
	// RVA: 0x28ca3c4 VA: 0x7594ee23c4
	public Void _InitData() { }
	// RVA: 0x28cae4c VA: 0x7594ee2e4c
	private Void _OnClick(String id, ItemType itemType) { }
	// RVA: 0x28caf30 VA: 0x7594ee2f30
	public Void .ctor() { }
}
```