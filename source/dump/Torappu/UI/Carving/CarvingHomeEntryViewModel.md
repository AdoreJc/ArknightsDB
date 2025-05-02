# CarvingHomeEntryViewModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `String actId`

- `Int32 enterSequence`

- `Int32 focusIndex`

- `Boolean isPlaying`

- `String m_playingChallengeId`


## Properties

- `CarvingHomeEntryItemViewModel focusItem`

- `Boolean isPrevItemNew`

- `Boolean isNextItemNew`

- `Int32 itemCount`


## Methods

- `CarvingHomeEntryItemViewModel get_focusItem()`

- `Boolean get_isPrevItemNew()`

- `Boolean get_isNextItemNew()`

- `Int32 get_itemCount()`

- `Void LoadData(String)`

- `Void RefreshData()`

- `Void FocusLastPlayChallengeIfNeed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingHomeEntryViewModel : IHotfixable
{
	public const Int32 DEFAULT_ENTER_SEQUENCE; // 0x0
	public String actId; // 0x10
	public Int32 enterSequence; // 0x18
	public List`1 itemModelList; // 0x20
	public Int32 focusIndex; // 0x28
	public Boolean isPlaying; // 0x2c
	private String m_playingChallengeId; // 0x30
	private static DelegateBridge __Hotfix0_get_focusItem; // 0x0
	private static DelegateBridge __Hotfix0_get_isPrevItemNew; // 0x8
	private static DelegateBridge __Hotfix0_get_isNextItemNew; // 0x10
	private static DelegateBridge __Hotfix0_get_itemCount; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_RefreshData; // 0x28
	private static DelegateBridge __Hotfix0_FocusLastPlayChallengeIfNeed; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public CarvingHomeEntryItemViewModel focusItem { get; }
	public Boolean isPrevItemNew { get; }
	public Boolean isNextItemNew { get; }
	public Int32 itemCount { get; }

	// RVA: 0x2d928c8 VA: 0x75953aa8c8
	public CarvingHomeEntryItemViewModel get_focusItem() { }
	// RVA: 0x2d92a98 VA: 0x75953aaa98
	public Boolean get_isPrevItemNew() { }
	// RVA: 0x2d92b54 VA: 0x75953aab54
	public Boolean get_isNextItemNew() { }
	// RVA: 0x2d92a18 VA: 0x75953aaa18
	public Int32 get_itemCount() { }
	// RVA: 0x2d93fd0 VA: 0x75953abfd0
	public Void LoadData(String activityId) { }
	// RVA: 0x2d94648 VA: 0x75953ac648
	public Void RefreshData() { }
	// RVA: 0x2d9405c VA: 0x75953ac05c
	public Void FocusLastPlayChallengeIfNeed() { }
	// RVA: 0x2d96708 VA: 0x75953ae708
	public Void .ctor() { }
}
```