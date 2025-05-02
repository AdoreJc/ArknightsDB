# ArchiveEndbookListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveEndbookEntryPickerView _pickerView`

- `Image _blurbg`

- `GameObject _lockedBg`

- `SimpleLayoutContent _circleContent`

- `UIAnimationLocation _switchAnimLocation`

- `ActArchiveController m_controller`

- `Boolean m_isInited`

- `Int32 m_cachedIndex`

- `CircleAdapter m_circleAdapter`

- `EndbookModel m_cachedViewModel`


## Properties

- `ActArchiveController controller`


## Methods

- `ActArchiveController get_controller()`

- `Void set_controller(ActArchiveController)`

- `Void _InitIfNot()`

- `Void _PlaySwitchAnim()`

- `Void _OnIndexUpdate(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveEndbookListDataBinder : DataBinder`1
{
	private ArchiveEndbookEntryPickerView _pickerView; // 0x20
	private Image _blurbg; // 0x28
	private GameObject _lockedBg; // 0x30
	private SimpleLayoutContent _circleContent; // 0x38
	private UIAnimationLocation _switchAnimLocation; // 0x40
	private ActArchiveController m_controller; // 0x50
	private Boolean m_isInited; // 0x58
	private Int32 m_cachedIndex; // 0x5c
	private CircleAdapter m_circleAdapter; // 0x60
	private EndbookModel m_cachedViewModel; // 0x68
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__PlaySwitchAnim; // 0x20
	private static DelegateBridge __Hotfix0__OnIndexUpdate; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private ActArchiveController controller { get; set; }

	// RVA: 0x30506f0 VA: 0x75956686f0
	private ActArchiveController get_controller() { }
	// RVA: 0x304c4b8 VA: 0x75956644b8
	public Void set_controller(ActArchiveController value) { }
	// RVA: 0x30509a4 VA: 0x75956689a4
	public override Void OnValueChanged(EndbookProperty property) { }
	// RVA: 0x3050758 VA: 0x7595668758
	private Void _InitIfNot() { }
	// RVA: 0x3050f90 VA: 0x7595668f90
	private Void _PlaySwitchAnim() { }
	// RVA: 0x3051088 VA: 0x7595669088
	private Void _OnIndexUpdate(Int32 index) { }
	// RVA: 0x3051264 VA: 0x7595669264
	public Void .ctor() { }
}
```