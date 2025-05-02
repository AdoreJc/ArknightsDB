# Act5D0MissionItemObj

**Namespace:** `Torappu.Activity.Act5D0`


## Fields

- `Image _bg`

- `Text _difficulty`

- `Text _difficultyAppend`

- `Text _reward`

- `Text _rewardAppend`

- `Text _title`

- `Text _desc`

- `Text _rewardItemCount`

- `Image _crossImg`

- `GameObject _finishMask`

- `CanvasGroup _itemCanvas`

- `Transform _itemViewContainer`

- `Single _itemCardScaleFactor`

- `UIStringEvent clickEvent`

- `UIItemCard m_itemCard`

- `Boolean m_itemInited`


## Methods

- `Void RenderItemPart(Act5D0MissionViewModel)`

- `Void InitData(Act5D0MissionViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Act5D0MissionItemObj : MonoBehaviour, IHotfixable
{
	private Image _bg; // 0x18
	private Text _difficulty; // 0x20
	private Text _difficultyAppend; // 0x28
	private Text _reward; // 0x30
	private Text _rewardAppend; // 0x38
	private Text _title; // 0x40
	private Text _desc; // 0x48
	private Text _rewardItemCount; // 0x50
	private Image _crossImg; // 0x58
	private GameObject _finishMask; // 0x60
	private CanvasGroup _itemCanvas; // 0x68
	private Transform _itemViewContainer; // 0x70
	private Single _itemCardScaleFactor; // 0x78
	public UIStringEvent clickEvent; // 0x80
	private UIItemCard m_itemCard; // 0x88
	private Boolean m_itemInited; // 0x90
	private static DelegateBridge __Hotfix0_RenderItemPart; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31c0dc4 VA: 0x75957d8dc4
	public Void RenderItemPart(Act5D0MissionViewModel viewModel) { }
	// RVA: 0x31c0cb4 VA: 0x75957d8cb4
	public Void InitData(Act5D0MissionViewModel viewModel) { }
	// RVA: 0x31c1350 VA: 0x75957d9350
	public Void .ctor() { }
}
```