# HandBookCardView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `String m_charId`

- `Single m_lvl`

- `Single m_friendship`

- `Int32 m_coorX`

- `Int32 m_coorY`

- `Animator _cardScaleAnimator`

- `Image _charHeadIconGrey`

- `Image _charHeadIcon`

- `Image _smallIcon`

- `Text _nameText`

- `Text _numberShow`

- `GameObject _selected`

- `GameObject _haveMoreLine`

- `UICommonTrackPoint _updatedTrackPoint`

- `Single _trackStartPos`

- `Single _trackEndPos`

- `TrackPointViewProperty m_updatedTrackPointProperty`

- `HandBookCardViewModel m_cardData`

- `HandBookScrollView m_parentView`

- `Boolean <detailFlag>k__BackingField`

- `Vector3 m_initPos`

- `String m_powerId`

- `Single m_propertyZoomValue`


## Properties

- `HandBookCardViewModel cardData`

- `HandBookScrollView parentView`

- `Boolean detailFlag`

- `Vector3 initPos`

- `Single lvl`

- `String charID`

- `String powerId`

- `Boolean selected`

- `Single zoomValue`


## Methods

- `HandBookCardViewModel get_cardData()`

- `Void set_parentView(HandBookScrollView)`

- `Boolean get_detailFlag()`

- `Void set_detailFlag(Boolean)`

- `Vector3 get_initPos()`

- `Void set_initPos(Vector3)`

- `Single get_lvl()`

- `Void set_lvl(Single)`

- `String get_charID()`

- `Void set_charID(String)`

- `String get_powerId()`

- `Void set_selected(Boolean)`

- `Single get_zoomValue()`

- `Void set_zoomValue(Single)`

- `Void MoveFirstThread(Single, CARDSTATE)`

- `Void MoveSecondThread(Single, Boolean, Boolean)`

- `Void MoveThirdThread(Vector3, Single, Boolean)`

- `Void MoveForthThread()`

- `Void OnValueRefresh(HandBookScrollViewProperty)`

- `Void OnValueChanged(HandBookScrollViewProperty)`

- `IEnumerator _MoveSecondThread(Vector3)`

- `IEnumerator _MoveFirstThread(Vector3)`

- `IEnumerator _MoveMiddleFirstThread()`

- `Void LoadData(HandbookCardData)`

- `Void LoadData(HandBookCardViewModel, Boolean)`

- `Void UpdateTrackPoint()`

- `Void SetActiveFalse()`

- `Void OnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookCardView : MonoBehaviour, IHotfixable
{
	public String m_charId; // 0x18
	public Single m_lvl; // 0x20
	public Single m_friendship; // 0x24
	public Int32 m_coorX; // 0x28
	public Int32 m_coorY; // 0x2c
	private HandBookCardView[] _relations; // 0x30
	private Animator _cardScaleAnimator; // 0x38
	private Image _charHeadIconGrey; // 0x40
	private Image _charHeadIcon; // 0x48
	private Image _smallIcon; // 0x50
	private Text _nameText; // 0x58
	private Text _numberShow; // 0x60
	private GameObject _selected; // 0x68
	private GameObject _haveMoreLine; // 0x70
	private UICommonTrackPoint _updatedTrackPoint; // 0x78
	private Single _trackStartPos; // 0x80
	private Single _trackEndPos; // 0x84
	public List`1 lines; // 0x88
	private TrackPointViewProperty m_updatedTrackPointProperty; // 0x90
	private HandBookCardViewModel m_cardData; // 0x98
	private HandBookScrollView m_parentView; // 0xa0
	private Boolean <detailFlag>k__BackingField; // 0xa8
	private Vector3 m_initPos; // 0xac
	private String m_powerId; // 0xb8
	private Single m_propertyZoomValue; // 0xc0
	private static DelegateBridge __Hotfix0_get_cardData; // 0x0
	private static DelegateBridge __Hotfix0_set_parentView; // 0x8
	private static DelegateBridge __Hotfix0_get_detailFlag; // 0x10
	private static DelegateBridge __Hotfix0_set_detailFlag; // 0x18
	private static DelegateBridge __Hotfix0_get_initPos; // 0x20
	private static DelegateBridge __Hotfix0_set_initPos; // 0x28
	private static DelegateBridge __Hotfix0_get_lvl; // 0x30
	private static DelegateBridge __Hotfix0_set_lvl; // 0x38
	private static DelegateBridge __Hotfix0_get_charID; // 0x40
	private static DelegateBridge __Hotfix0_set_charID; // 0x48
	private static DelegateBridge __Hotfix0_get_powerId; // 0x50
	private static DelegateBridge __Hotfix0_set_selected; // 0x58
	private static DelegateBridge __Hotfix0_get_zoomValue; // 0x60
	private static DelegateBridge __Hotfix0_set_zoomValue; // 0x68
	private static DelegateBridge __Hotfix0_MoveFirstThread; // 0x70
	private static DelegateBridge __Hotfix0_MoveSecondThread; // 0x78
	private static DelegateBridge __Hotfix0_MoveThirdThread; // 0x80
	private static DelegateBridge __Hotfix0_MoveForthThread; // 0x88
	private static DelegateBridge __Hotfix0_OnValueRefresh; // 0x90
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x98
	private static DelegateBridge __Hotfix0__MoveSecondThread; // 0xa0
	private static DelegateBridge __Hotfix0__MoveFirstThread; // 0xa8
	private static DelegateBridge __Hotfix0__MoveMiddleFirstThread; // 0xb0
	private static DelegateBridge __Hotfix0_LoadData; // 0xb8
	private static DelegateBridge __Hotfix1_LoadData; // 0xc0
	private static DelegateBridge __Hotfix0_UpdateTrackPoint; // 0xc8
	private static DelegateBridge __Hotfix0_SetActiveFalse; // 0xd0
	private static DelegateBridge __Hotfix0_OnClicked; // 0xd8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe0

	public HandBookCardViewModel cardData { get; }
	public HandBookScrollView parentView { set; }
	public Boolean detailFlag { get; set; }
	public Vector3 initPos { get; set; }
	public Single lvl { get; set; }
	public String charID { get; set; }
	public String powerId { get; }
	public Boolean selected { set; }
	private Single zoomValue { get; set; }

	// RVA: 0x2eaa17c VA: 0x75954c217c
	public HandBookCardViewModel get_cardData() { }
	// RVA: 0x2eaa1e4 VA: 0x75954c21e4
	public Void set_parentView(HandBookScrollView value) { }
	// RVA: 0x2eaa268 VA: 0x75954c2268
	public Boolean get_detailFlag() { }
	// RVA: 0x2eaa2d0 VA: 0x75954c22d0
	private Void set_detailFlag(Boolean value) { }
	// RVA: 0x2eaa350 VA: 0x75954c2350
	public Vector3 get_initPos() { }
	// RVA: 0x2eaa3b8 VA: 0x75954c23b8
	public Void set_initPos(Vector3 value) { }
	// RVA: 0x2eaa454 VA: 0x75954c2454
	public Single get_lvl() { }
	// RVA: 0x2eaa4bc VA: 0x75954c24bc
	public Void set_lvl(Single value) { }
	// RVA: 0x2eaa538 VA: 0x75954c2538
	public String get_charID() { }
	// RVA: 0x2eaa5a0 VA: 0x75954c25a0
	public Void set_charID(String value) { }
	// RVA: 0x2eaa624 VA: 0x75954c2624
	public String get_powerId() { }
	// RVA: 0x2e9da48 VA: 0x75954b5a48
	public Void set_selected(Boolean value) { }
	// RVA: 0x2eaa68c VA: 0x75954c268c
	private Single get_zoomValue() { }
	// RVA: 0x2eaa70c VA: 0x75954c270c
	private Void set_zoomValue(Single value) { }
	// RVA: 0x2eaa788 VA: 0x75954c2788
	public Void MoveFirstThread(Single zoomValue, CARDSTATE cardState) { }
	// RVA: 0x2eaa874 VA: 0x75954c2874
	public Void MoveSecondThread(Single zoomValue, Boolean zoomFlag, Boolean quickAnim) { }
	// RVA: 0x2eaa9d8 VA: 0x75954c29d8
	public Void MoveThirdThread(Vector3 pos, Single angle, Boolean quickAnim) { }
	// RVA: 0x2eaab9c VA: 0x75954c2b9c
	public Void MoveForthThread() { }
	// RVA: 0x2eaac40 VA: 0x75954c2c40
	public Void OnValueRefresh(HandBookScrollViewProperty property) { }
	// RVA: 0x2eaafec VA: 0x75954c2fec
	public Void OnValueChanged(HandBookScrollViewProperty property) { }
	// RVA: 0x2eab6c0 VA: 0x75954c36c0
	private IEnumerator _MoveSecondThread(Vector3 pos) { }
	// RVA: 0x2eab530 VA: 0x75954c3530
	private IEnumerator _MoveFirstThread(Vector3 pos) { }
	// RVA: 0x2eab614 VA: 0x75954c3614
	private IEnumerator _MoveMiddleFirstThread() { }
	// RVA: 0x2eab81c VA: 0x75954c381c
	public Void LoadData(HandbookCardData cardData) { }
	// RVA: 0x2e9d7cc VA: 0x75954b57cc
	public Void LoadData(HandBookCardViewModel cardData, Boolean needTrackPoint) { }
	// RVA: 0x2eab968 VA: 0x75954c3968
	public Void UpdateTrackPoint() { }
	// RVA: 0x2eaba30 VA: 0x75954c3a30
	public Void SetActiveFalse() { }
	// RVA: 0x2eabac0 VA: 0x75954c3ac0
	public Void OnClicked() { }
	// RVA: 0x2eabba0 VA: 0x75954c3ba0
	public Void .ctor() { }
}
```