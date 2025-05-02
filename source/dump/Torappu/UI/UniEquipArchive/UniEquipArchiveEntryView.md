# UniEquipArchiveEntryView

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `SimpleLayoutContent _infoContent`

- `Text _txtNewEditionCnt`

- `UniEquipArchiveEntryCollectionNewEditionsAdapter _newEditionsAdapter`

- `LoopHorizontalScrollRect _horizontalScroll`

- `UICommonTrackPoint _charNewUniEquipTrackPoint`

- `UIAnimationLocation _animShow`

- `UIAnimationLocation _switchIconAnim`

- `Boolean m_isInited`

- `UIStateFinder m_stateFinder`

- `UniEquipArchiveEntryViewModel m_cachedViewModel`

- `UniEquipArchiveEntryCollectionInfoListAdapter m_infoListAdapter`

- `TrackPointViewProperty m_charNewUniEquipTrackPointProperty`

- `Int32 m_cachedEnterSeq`

- `Tween m_showTween`

- `Tween m_switchIconTween`


## Methods

- `Void _InitIfNot()`

- `Void _ShowEnterAnim()`

- `Void _UpdateTrackPoint()`

- `Void _PlaySwitchInfoAnim()`

- `Void OnOpenCharacterClick()`

- `Void OnSwitchInfoTypeClick()`

- `Void OnOpenModuleListClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveEntryView : DataBinder`1
{
	private SimpleLayoutContent _infoContent; // 0x20
	private Text _txtNewEditionCnt; // 0x28
	private UniEquipArchiveEntryCollectionNewEditionsAdapter _newEditionsAdapter; // 0x30
	private LoopHorizontalScrollRect _horizontalScroll; // 0x38
	private UICommonTrackPoint _charNewUniEquipTrackPoint; // 0x40
	private UIAnimationLocation _animShow; // 0x48
	private UIAnimationLocation _switchIconAnim; // 0x58
	private Boolean m_isInited; // 0x68
	private UIStateFinder m_stateFinder; // 0x70
	private UniEquipArchiveEntryViewModel m_cachedViewModel; // 0x80
	private UniEquipArchiveEntryCollectionInfoListAdapter m_infoListAdapter; // 0x88
	private TrackPointViewProperty m_charNewUniEquipTrackPointProperty; // 0x90
	private Int32 m_cachedEnterSeq; // 0x98
	private Tween m_showTween; // 0xa0
	private Tween m_switchIconTween; // 0xa8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__ShowEnterAnim; // 0x10
	private static DelegateBridge __Hotfix0__UpdateTrackPoint; // 0x18
	private static DelegateBridge __Hotfix0__PlaySwitchInfoAnim; // 0x20
	private static DelegateBridge __Hotfix0_OnOpenCharacterClick; // 0x28
	private static DelegateBridge __Hotfix0_OnSwitchInfoTypeClick; // 0x30
	private static DelegateBridge __Hotfix0_OnOpenModuleListClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x22ef1c0 VA: 0x75949071c0
	public override Void OnValueChanged(UniEquipArchiveEntryProperty property) { }
	// RVA: 0x22ef4cc VA: 0x75949074cc
	private Void _InitIfNot() { }
	// RVA: 0x22ef3b4 VA: 0x75949073b4
	private Void _ShowEnterAnim() { }
	// RVA: 0x22ef614 VA: 0x7594907614
	private Void _UpdateTrackPoint() { }
	// RVA: 0x22ef81c VA: 0x759490781c
	private Void _PlaySwitchInfoAnim() { }
	// RVA: 0x22ef94c VA: 0x759490794c
	public Void OnOpenCharacterClick() { }
	// RVA: 0x22efa00 VA: 0x7594907a00
	public Void OnSwitchInfoTypeClick() { }
	// RVA: 0x22efabc VA: 0x7594907abc
	public Void OnOpenModuleListClick() { }
	// RVA: 0x22efb70 VA: 0x7594907b70
	public Void .ctor() { }
}
```