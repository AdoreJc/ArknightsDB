# RoguelikeInitConfirmBtn

**Namespace:** `Torappu.UI.Roguelike.Init`


## Fields

- `AnimationWrapper _anim`

- `Action m_onClicked`


## Methods

- `Void _InitIfNot()`

- `Void InjectBtnEvents(Action)`

- `Void EventOnConfirm()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class RoguelikeInitConfirmBtn : MonoBehaviour, IHotfixable
{
	private AnimationWrapper _anim; // 0x18
	private const String ARROW_ANIM; // 0x0
	private Action m_onClicked; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_InjectBtnEvents; // 0x8
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b85478 VA: 0x759519d478
	private Void _InitIfNot() { }
	// RVA: 0x2b85518 VA: 0x759519d518
	public Void InjectBtnEvents(Action onClick) { }
	// RVA: 0x2b855a4 VA: 0x759519d5a4
	public Void EventOnConfirm() { }
	// RVA: 0x2b85620 VA: 0x759519d620
	public Void .ctor() { }
}
```