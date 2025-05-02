# TuningHandbookView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `Text _textName`

- `Text _textAlias`

- `Text _textDes`

- `Image _imgMusic`

- `GameObject _objNormalMsg`

- `GameObject _objSpMsg`

- `Image _imgSpMusic`

- `Text _textSpName`

- `Text _textSpAlias`

- `Text _textSpDes`

- `SimpleLayoutContent _layoutContentEmotionDetail`

- `SimpleLayoutContent _layoutContentFormulaDetail`

- `Boolean m_inited`

- `UIPageFinder m_pageFinder`

- `TuningHandbookViewModel m_model`

- `EmotionDetailAdapter m_emotionDetailAdapter`

- `FormulaDetailAdapter m_formulaDetailAdapter`


## Methods

- `Void set_onEmotionClickedAction(Action`1)`

- `Void _InitIfNot()`

- `Void _UpdateMusicMessage()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHandbookView : DataBinder`1, IHotfixable
{
	private Text _textName; // 0x20
	private Text _textAlias; // 0x28
	private Text _textDes; // 0x30
	private Image _imgMusic; // 0x38
	private GameObject _objNormalMsg; // 0x40
	private GameObject _objSpMsg; // 0x48
	private Image _imgSpMusic; // 0x50
	private Text _textSpName; // 0x58
	private Text _textSpAlias; // 0x60
	private Text _textSpDes; // 0x68
	private SimpleLayoutContent _layoutContentEmotionDetail; // 0x70
	private SimpleLayoutContent _layoutContentFormulaDetail; // 0x78
	private Boolean m_inited; // 0x80
	private UIPageFinder m_pageFinder; // 0x88
	private TuningHandbookViewModel m_model; // 0x98
	private EmotionDetailAdapter m_emotionDetailAdapter; // 0xa0
	private FormulaDetailAdapter m_formulaDetailAdapter; // 0xa8
	private Action`1 <onEmotionClickedAction>k__BackingField; // 0xb0
	private static DelegateBridge __Hotfix0_get_onEmotionClickedAction; // 0x0
	private static DelegateBridge __Hotfix0_set_onEmotionClickedAction; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__UpdateMusicMessage; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onEmotionClickedAction { get; set; }

	// RVA: 0x2324258 VA: 0x759493c258
	private Action`1 get_onEmotionClickedAction() { }
	// RVA: 0x23242c0 VA: 0x759493c2c0
	public Void set_onEmotionClickedAction(Action`1 value) { }
	// RVA: 0x2324344 VA: 0x759493c344
	private Void _InitIfNot() { }
	// RVA: 0x2324590 VA: 0x759493c590
	private Void _UpdateMusicMessage() { }
	// RVA: 0x23247f4 VA: 0x759493c7f4
	public override Void OnValueChanged(TuningHandbookProperty property) { }
	// RVA: 0x2324904 VA: 0x759493c904
	public Void .ctor() { }
}
```