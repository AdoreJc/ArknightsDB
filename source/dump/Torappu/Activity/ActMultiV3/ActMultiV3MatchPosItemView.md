# ActMultiV3MatchPosItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `GameObject _unselectPartGO`

- `GameObject _selectPartGO`

- `GameObject _lockPartGO`

- `Text _textName`

- `Color _colorTextUnselect`

- `Color _colorTextSelect`

- `Image _imgIconUnselect`

- `Image _imgIconSelect`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `ActMultiV3MatchPosModel m_posModel`


## Methods

- `Void Render(ActMultiV3MatchPosModel, Boolean)`

- `Void EventOnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MatchPosItemView : MonoBehaviour, IHotfixable
{
	private GameObject _unselectPartGO; // 0x18
	private GameObject _selectPartGO; // 0x20
	private GameObject _lockPartGO; // 0x28
	private Text _textName; // 0x30
	private Color _colorTextUnselect; // 0x38
	private Color _colorTextSelect; // 0x48
	private Image _imgIconUnselect; // 0x58
	private Image _imgIconSelect; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private UIStateFinder m_stateFinder; // 0x78
	private ActMultiV3MatchPosModel m_posModel; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3127ba0 VA: 0x759573fba0
	public Void Render(ActMultiV3MatchPosModel posModel, Boolean isSelect) { }
	// RVA: 0x3127d54 VA: 0x759573fd54
	public Void EventOnItemClick() { }
	// RVA: 0x3127e78 VA: 0x759573fe78
	public Void .ctor() { }
}
```