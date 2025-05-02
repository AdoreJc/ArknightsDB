# TuningHandbookFormulaItemView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `GameObject _objUnlockItem`

- `GameObject _objLockItem`

- `Text _txtFormula`

- `Boolean m_hasInited`

- `TuningHandbookFormulaViewModel m_formulaNodeModel`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(TuningHandbookFormulaViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHandbookFormulaItemView : MonoBehaviour, IHotfixable
{
	private GameObject _objUnlockItem; // 0x18
	private GameObject _objLockItem; // 0x20
	private Image[] _imgFormula; // 0x28
	private Text _txtFormula; // 0x30
	private Boolean m_hasInited; // 0x38
	private TuningHandbookFormulaViewModel m_formulaNodeModel; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2321d84 VA: 0x7594939d84
	public Void Render(TuningHandbookFormulaViewModel model) { }
	// RVA: 0x2322078 VA: 0x759493a078
	private Void _InitIfNot() { }
	// RVA: 0x23220ec VA: 0x759493a0ec
	public Void .ctor() { }
}
```