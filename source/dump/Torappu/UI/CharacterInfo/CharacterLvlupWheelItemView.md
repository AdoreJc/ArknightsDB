# CharacterLvlupWheelItemView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Text _txtNum`

- `Text _txtNumShadow`

- `Graphic _imgMax`

- `Color _maxEnabledColor`

- `Color _maxDisabledColor`

- `Single _sizeUnselect`

- `Single _sizeSelected`

- `Int32 m_curNum`

- `Int32 m_pageIndex`

- `StyleStatus m_styleStatus`


## Methods

- `Single GetPreferSize(Single)`

- `Void Render(Param, Boolean)`

- `Void _UdpateTextColor(ColorParam, StyleStatus)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupWheelItemView : MonoBehaviour, IHotfixable
{
	private Text _txtNum; // 0x18
	private Text _txtNumShadow; // 0x20
	private Graphic _imgMax; // 0x28
	private Color _maxEnabledColor; // 0x30
	private Color _maxDisabledColor; // 0x40
	private Single _sizeUnselect; // 0x50
	private Single _sizeSelected; // 0x54
	private Int32 m_curNum; // 0x58
	private Int32 m_pageIndex; // 0x5c
	private StyleStatus m_styleStatus; // 0x60
	private Action`1 m_onItemClicked; // 0x68
	private static DelegateBridge __Hotfix0_GetPreferSize; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__UdpateTextColor; // 0x10
	private static DelegateBridge __Hotfix0__GetStyleStatus; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2d790b0 VA: 0x75953910b0
	public Single GetPreferSize(Single pageDistance) { }
	// RVA: 0x2d79150 VA: 0x7595391150
	private Void Render(Param param, Boolean isSelected) { }
	// RVA: 0x2d7943c VA: 0x759539143c
	private Void _UdpateTextColor(ColorParam param, StyleStatus status) { }
	// RVA: 0x2d7934c VA: 0x759539134c
	private static StyleStatus _GetStyleStatus(Boolean isAttainable, Boolean isSelected) { }
	// RVA: 0x2d7967c VA: 0x759539167c
	public Void EventOnClicked() { }
	// RVA: 0x2d79704 VA: 0x7595391704
	public Void .ctor() { }
}
```