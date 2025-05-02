# RoguelikeInitBGPanel

**Namespace:** `Torappu.UI.Roguelike.Init`


## Fields

- `Text _stepTitleLabel`

- `Single _stepPrgAnimDur`

- `Scrollbar _stepPrg`

- `Transform _stepPoints`

- `RoguelikeInitStyle m_style`

- `Int32 m_step`

- `Int32 m_maxStep`

- `Tween m_tweener`


## Methods

- `Single _CurPrg()`

- `Void _SetPrg(Single)`

- `Void _UpdatePoint()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class RoguelikeInitBGPanel : RoguelikeInitPanel
{
	private Text _stepTitleLabel; // 0x20
	private Single _stepPrgAnimDur; // 0x28
	private Scrollbar _stepPrg; // 0x30
	private Transform _stepPoints; // 0x38
	private RoguelikeInitStyle m_style; // 0x40
	private Int32 m_step; // 0x48
	private Int32 m_maxStep; // 0x4c
	private Tween m_tweener; // 0x50
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__CurPrg; // 0x8
	private static DelegateBridge __Hotfix0__SetPrg; // 0x10
	private static DelegateBridge __Hotfix0__UpdatePoint; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2b84794 VA: 0x759519c794
	public override Void OnValueChanged(RoguelikeInitModelProperty property) { }
	// RVA: 0x2b84c74 VA: 0x759519cc74
	private Single _CurPrg() { }
	// RVA: 0x2b84d24 VA: 0x759519cd24
	private Void _SetPrg(Single v) { }
	// RVA: 0x2b84aec VA: 0x759519caec
	private Void _UpdatePoint() { }
	// RVA: 0x2b84ec8 VA: 0x759519cec8
	public Void .ctor() { }
}
```