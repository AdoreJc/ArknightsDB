# Act3D0GachaBoxRightPartView

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Act3D0GachaBoxItem _boxItem`

- `Transform _container`

- `Act3D0GachaBoxSliderItem _slideItem`

- `Transform _slideContainer`

- `Act3D0GachaBoxDetailView _detailView`

- `UIStringEvent _onGachaTime`

- `UIStringEvent _onGachaTenTimes`

- `Image _buttonImg`

- `Text _buttonPrice`

- `Text _buttonTencePrice`

- `Text _buttonTenceTimes`

- `Text _boxIndex`

- `GameObject _leftBtn`

- `GameObject _rightBtn`

- `GameObject _oneTimeBtn`

- `GameObject _tenTimeBtn`

- `GameObject _oneTimeBan`

- `GameObject _tenTimeBan`

- `GameObject _oneTimeMin`

- `GameObject _tenTimeMin`

- `GameObject _remainPart`

- `Text _remainCount`

- `Int32 m_focusIndex`

- `String m_focusId`

- `Int32 m_gachaTimes`

- `Boolean m_isInited`


## Properties

- `Int32 gachaTimes`

- `Act3D0CampResHolder resHolder`


## Methods

- `Int32 get_gachaTimes()`

- `Act3D0CampResHolder get_resHolder()`

- `Void OnClick()`

- `Void OnClickTenTimes()`

- `Void InitInfo(List`1, String)`

- `Void OnFocus(Int32)`

- `Void OnFocus(String)`

- `Void Refresh()`

- `Void Refresh(List`1)`

- `Void _OnFocus()`

- `Void RenderInfo(List`1)`

- `Void CheckTimes()`

- `Void LeftOne()`

- `Void RightOne()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0GachaBoxRightPartView : MonoBehaviour, IHotfixable
{
	private Act3D0GachaBoxItem _boxItem; // 0x18
	private Transform _container; // 0x20
	private Act3D0GachaBoxSliderItem _slideItem; // 0x28
	private Transform _slideContainer; // 0x30
	private Act3D0GachaBoxDetailView _detailView; // 0x38
	private UIStringEvent _onGachaTime; // 0x40
	private UIStringEvent _onGachaTenTimes; // 0x48
	private Image _buttonImg; // 0x50
	private Text _buttonPrice; // 0x58
	private Text _buttonTencePrice; // 0x60
	private Text _buttonTenceTimes; // 0x68
	private Text _boxIndex; // 0x70
	private GameObject _leftBtn; // 0x78
	private GameObject _rightBtn; // 0x80
	private GameObject _oneTimeBtn; // 0x88
	private GameObject _tenTimeBtn; // 0x90
	private GameObject _oneTimeBan; // 0x98
	private GameObject _tenTimeBan; // 0xa0
	private GameObject _oneTimeMin; // 0xa8
	private GameObject _tenTimeMin; // 0xb0
	private GameObject _remainPart; // 0xb8
	private Text _remainCount; // 0xc0
	public Dictionary`2 infinitePercent; // 0xc8
	private Int32 m_focusIndex; // 0xd0
	private String m_focusId; // 0xd8
	private Int32 m_gachaTimes; // 0xe0
	private List`1 m_boxItemList; // 0xe8
	private List`1 m_sliderItem; // 0xf0
	private List`1 m_boxInfo; // 0xf8
	private Boolean m_isInited; // 0x100
	private static DelegateBridge __Hotfix0_get_gachaTimes; // 0x0
	private static DelegateBridge __Hotfix0_get_resHolder; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0_OnClickTenTimes; // 0x18
	private static DelegateBridge __Hotfix0_InitInfo; // 0x20
	private static DelegateBridge __Hotfix0_OnFocus; // 0x28
	private static DelegateBridge __Hotfix1_OnFocus; // 0x30
	private static DelegateBridge __Hotfix0_Refresh; // 0x38
	private static DelegateBridge __Hotfix1_Refresh; // 0x40
	private static DelegateBridge __Hotfix0__OnFocus; // 0x48
	private static DelegateBridge __Hotfix0_RenderInfo; // 0x50
	private static DelegateBridge __Hotfix0_CheckTimes; // 0x58
	private static DelegateBridge __Hotfix0_LeftOne; // 0x60
	private static DelegateBridge __Hotfix0_RightOne; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Int32 gachaTimes { get; }
	public Act3D0CampResHolder resHolder { get; }

	// RVA: 0x322f344 VA: 0x7595847344
	public Int32 get_gachaTimes() { }
	// RVA: 0x32339d8 VA: 0x759584b9d8
	public Act3D0CampResHolder get_resHolder() { }
	// RVA: 0x3233a3c VA: 0x759584ba3c
	public Void OnClick() { }
	// RVA: 0x3233b14 VA: 0x759584bb14
	public Void OnClickTenTimes() { }
	// RVA: 0x322f548 VA: 0x7595847548
	public Void InitInfo(List`1 boxInfo, String defaultBoxId) { }
	// RVA: 0x3234210 VA: 0x759584c210
	public Void OnFocus(Int32 focusIndex) { }
	// RVA: 0x3230468 VA: 0x7595848468
	public Void OnFocus(String focusId) { }
	// RVA: 0x322ebac VA: 0x7595846bac
	public Void Refresh() { }
	// RVA: 0x322fff0 VA: 0x7595847ff0
	public Void Refresh(List`1 boxInfo) { }
	// RVA: 0x3233d94 VA: 0x759584bd94
	private Void _OnFocus() { }
	// RVA: 0x3233bec VA: 0x759584bbec
	public Void RenderInfo(List`1 boxInfo) { }
	// RVA: 0x323436c VA: 0x759584c36c
	private Void CheckTimes() { }
	// RVA: 0x32347c0 VA: 0x759584c7c0
	public Void LeftOne() { }
	// RVA: 0x323487c VA: 0x759584c87c
	public Void RightOne() { }
	// RVA: 0x323495c VA: 0x759584c95c
	public Void .ctor() { }
}
```