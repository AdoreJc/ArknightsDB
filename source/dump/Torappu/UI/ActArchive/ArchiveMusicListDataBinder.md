# ArchiveMusicListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `AutoFocusScrollView _scrollView`

- `SimpleLayoutContent _viewContainer`

- `Sprite _imgListItemTitleNormal`

- `MusicDiscView _musicDiscView`

- `MusicHomeThemeDiscRightView _musicHomeThemeDiscRightView`

- `MusicHomeThemeButtonView _musicHomeThemeButtonView`

- `Boolean m_hasInited`

- `Int32 m_currCardIndex`

- `ArchiveMusicListAdapter m_listAdapter`

- `ActArchiveController m_controller`

- `ArchiveMusicModel m_cachedModel`

- `MusicItemModel m_pendingModel`

- `String m_cachedSelectedMusicId`

- `String m_cachedHomeMusicId`

- `Sequence m_sequence`


## Properties

- `ActArchiveController controller`

- `ArchiveMusicModel model`


## Methods

- `ActArchiveController get_controller()`

- `Void set_controller(ActArchiveController)`

- `ArchiveMusicModel get_model()`

- `Void _InitIfNot()`

- `Void _ResetPosition()`

- `Void _RefreshHomeMusicId()`

- `Void _RefreshSelectedMusicId()`

- `Void _BeforeSwitchAnim()`

- `Void _AfterSwitchAnim()`

- `Void _ShowMusicItem(MusicItemModel)`

- `Void _SwitchItemCard(Int32, Int32, MusicItemModel)`

- `Int64 _BGMInstId()`

- `Void RefreshBGM()`

- `Void ClearBGM()`

- `IEnumerator FocusOnSelectedItem(Boolean, Single)`

- `Void <_SwitchItemCard>b__33_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveMusicListDataBinder : DataBinder`1
{
	private AutoFocusScrollView _scrollView; // 0x20
	private SimpleLayoutContent _viewContainer; // 0x28
	private Sprite _imgListItemTitleNormal; // 0x30
	private List`1 _cardViewList; // 0x38
	private MusicDiscView _musicDiscView; // 0x40
	private MusicHomeThemeDiscRightView _musicHomeThemeDiscRightView; // 0x48
	private MusicHomeThemeButtonView _musicHomeThemeButtonView; // 0x50
	private Boolean m_hasInited; // 0x58
	private Int32 m_currCardIndex; // 0x5c
	private ArchiveMusicListAdapter m_listAdapter; // 0x60
	private ActArchiveController m_controller; // 0x68
	private ArchiveMusicModel m_cachedModel; // 0x70
	private MusicItemModel m_pendingModel; // 0x78
	private String m_cachedSelectedMusicId; // 0x80
	private String m_cachedHomeMusicId; // 0x88
	private Sequence m_sequence; // 0x90
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_get_model; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__ResetPosition; // 0x28
	private static DelegateBridge __Hotfix0__RefreshHomeMusicId; // 0x30
	private static DelegateBridge __Hotfix0__RefreshSelectedMusicId; // 0x38
	private static DelegateBridge __Hotfix0__BeforeSwitchAnim; // 0x40
	private static DelegateBridge __Hotfix0__AfterSwitchAnim; // 0x48
	private static DelegateBridge __Hotfix0__ShowMusicItem; // 0x50
	private static DelegateBridge __Hotfix0__SwitchItemCard; // 0x58
	private static DelegateBridge __Hotfix0__BGMInstId; // 0x60
	private static DelegateBridge __Hotfix0_RefreshBGM; // 0x68
	private static DelegateBridge __Hotfix0_ClearBGM; // 0x70
	private static DelegateBridge __Hotfix0_FocusOnSelectedItem; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	private ActArchiveController controller { get; set; }
	public ArchiveMusicModel model { get; }

	// RVA: 0x305e5a8 VA: 0x75956765a8
	private ActArchiveController get_controller() { }
	// RVA: 0x305cc60 VA: 0x7595674c60
	public Void set_controller(ActArchiveController value) { }
	// RVA: 0x305e714 VA: 0x7595676714
	public ArchiveMusicModel get_model() { }
	// RVA: 0x305e77c VA: 0x759567677c
	public override Void OnValueChanged(MusicProperty property) { }
	// RVA: 0x305e610 VA: 0x7595676610
	private Void _InitIfNot() { }
	// RVA: 0x305e994 VA: 0x7595676994
	private Void _ResetPosition() { }
	// RVA: 0x305eb58 VA: 0x7595676b58
	private Void _RefreshHomeMusicId() { }
	// RVA: 0x305ebd4 VA: 0x7595676bd4
	private Void _RefreshSelectedMusicId() { }
	// RVA: 0x305f790 VA: 0x7595677790
	private Void _BeforeSwitchAnim() { }
	// RVA: 0x305fdd0 VA: 0x7595677dd0
	private Void _AfterSwitchAnim() { }
	// RVA: 0x305f810 VA: 0x7595677810
	private Void _ShowMusicItem(MusicItemModel model) { }
	// RVA: 0x306003c VA: 0x759567803c
	private Void _SwitchItemCard(Int32 cardNeedToHide, Int32 cardNeedToShow, MusicItemModel newModel) { }
	// RVA: 0x30605a4 VA: 0x75956785a4
	private Int64 _BGMInstId() { }
	// RVA: 0x305cebc VA: 0x7595674ebc
	public Void RefreshBGM() { }
	// RVA: 0x305d034 VA: 0x7595675034
	public Void ClearBGM() { }
	// RVA: 0x305d3e8 VA: 0x75956753e8
	public IEnumerator FocusOnSelectedItem(Boolean fastMode, Single duration) { }
	// RVA: 0x3060640 VA: 0x7595678640
	public Void .ctor() { }
	// RVA: 0x3060714 VA: 0x7595678714
	private Void <_SwitchItemCard>b__33_0() { }
}
```