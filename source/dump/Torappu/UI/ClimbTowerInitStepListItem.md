# ClimbTowerInitStepListItem

**Namespace:** `Torappu.UI`


## Fields

- `UIAtlasImage _imgBg`

- `Text _textStep`

- `Single _unselectedAlpha`

- `GameObject _dotGo`

- `LayoutElement _layoutElement`

- `Single _normalWidth`

- `Single _lastWidth`


## Methods

- `Void Render(Int32, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class ClimbTowerInitStepListItem : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _imgBg; // 0x18
	private Text _textStep; // 0x20
	private Single _unselectedAlpha; // 0x28
	private GameObject _dotGo; // 0x30
	private LayoutElement _layoutElement; // 0x38
	private Single _normalWidth; // 0x40
	private Single _lastWidth; // 0x44
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2109c68 VA: 0x7594721c68
	public Void Render(Int32 stepVal, Boolean isLast, Boolean isSelected) { }
	// RVA: 0x2109d8c VA: 0x7594721d8c
	public Void .ctor() { }
}
```