# ActMultiV3ProfileView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Text _completeMatchText`

- `Text _assistPlayerText`

- `Text _praisedText`

- `Text _titleText`

- `GameObject _newTrackPointObj`

- `RectTransform _newTrackPointContainer`

- `Text _doctorLevel`

- `Text _doctorName`

- `Text _doctorUid`

- `Image _bgImg`

- `Transform _avatarContainer`

- `Boolean m_inited`

- `Int32 m_cachedLoadSeqNum`

- `UIStateFinder m_stateFinder`

- `PlayerAvatarView m_avatarView`

- `GameObject m_newTitleObj`


## Methods

- `Void Render(ActMultiV3ManualProfileModel)`

- `Void OnClickTitle()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ProfileView : UIStylerApplier`1, IHotfixable
{
	private Text _completeMatchText; // 0x20
	private Text _assistPlayerText; // 0x28
	private Text _praisedText; // 0x30
	private Text _titleText; // 0x38
	private GameObject _newTrackPointObj; // 0x40
	private RectTransform _newTrackPointContainer; // 0x48
	private Text _doctorLevel; // 0x50
	private Text _doctorName; // 0x58
	private Text _doctorUid; // 0x60
	private Image _bgImg; // 0x68
	private Transform _avatarContainer; // 0x70
	private Boolean m_inited; // 0x78
	private Int32 m_cachedLoadSeqNum; // 0x7c
	private UIStateFinder m_stateFinder; // 0x80
	private PlayerAvatarView m_avatarView; // 0x90
	private GameObject m_newTitleObj; // 0x98
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClickTitle; // 0x8
	private static DelegateBridge __Hotfix0_OnApplyStyle; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30fc844 VA: 0x7595714844
	public Void Render(ActMultiV3ManualProfileModel profileModel) { }
	// RVA: 0x30fccfc VA: 0x7595714cfc
	public Void OnClickTitle() { }
	// RVA: 0x30fcda0 VA: 0x7595714da0
	protected override Void OnApplyStyle(NameCardV2SkinStyle style) { }
	// RVA: 0x30fcbc8 VA: 0x7595714bc8
	private Void _InitIfNot() { }
	// RVA: 0x30fce40 VA: 0x7595714e40
	public Void .ctor() { }
}
```