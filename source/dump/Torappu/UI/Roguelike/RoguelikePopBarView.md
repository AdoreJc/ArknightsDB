# RoguelikePopBarView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _currentBar`

- `Image _maxBar`

- `Text _maxCount1`

- `Text _maxCount2`

- `Text _currentCount1`

- `Single _maxLength`

- `UIPageListener m_pageListener`

- `Single m_cacheCurrentVal`

- `Single m_cacheMaxValue`


## Properties

- `UIPageListener pageListener`


## Methods

- `UIPageListener get_pageListener()`

- `Void RenderValue(Single, Single, Boolean, Single)`

- `Void LateUpdate()`

- `Void CheckPos()`

- `Void RenderTween(Int32, Int32, Single)`

- `Void RenderTween(Int32, Int32, Int32, Single)`

- `Void RenderTweenCurrent(Int32, Int32, Int32, Single)`

- `Coroutine _CoroutineWithPage(IEnumerator)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikePopBarView : MonoBehaviour, IHotfixable
{
	private Image _currentBar; // 0x18
	private Image _maxBar; // 0x20
	private Text _maxCount1; // 0x28
	private Text _maxCount2; // 0x30
	private Text _currentCount1; // 0x38
	private Single _maxLength; // 0x40
	private UIPageListener m_pageListener; // 0x48
	private Single m_cacheCurrentVal; // 0x50
	private Single m_cacheMaxValue; // 0x54
	private static DelegateBridge __Hotfix0_get_pageListener; // 0x0
	private static DelegateBridge __Hotfix0_RenderValue; // 0x8
	private static DelegateBridge __Hotfix0_LateUpdate; // 0x10
	private static DelegateBridge __Hotfix0_CheckPos; // 0x18
	private static DelegateBridge __Hotfix0_RenderTween; // 0x20
	private static DelegateBridge __Hotfix1_RenderTween; // 0x28
	private static DelegateBridge __Hotfix0_RenderTweenCurrent; // 0x30
	private static DelegateBridge __Hotfix0__CoroutineWithPage; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	protected UIPageListener pageListener { get; }

	// RVA: 0x29f589c VA: 0x759500d89c
	protected UIPageListener get_pageListener() { }
	// RVA: 0x29f5964 VA: 0x759500d964
	public Void RenderValue(Single currentValInput, Single maxVal, Boolean fixInCoro, Single delta) { }
	// RVA: 0x29f5d78 VA: 0x759500dd78
	public Void LateUpdate() { }
	// RVA: 0x29f5de0 VA: 0x759500dde0
	public Void CheckPos() { }
	// RVA: 0x29f5f9c VA: 0x759500df9c
	public Void RenderTween(Int32 currentVal, Int32 maxVal, Single duration) { }
	// RVA: 0x29f61a4 VA: 0x759500e1a4
	public Void RenderTween(Int32 currentVal, Int32 maxInitVal, Int32 maxTargetVal, Single duration) { }
	// RVA: 0x29f63d0 VA: 0x759500e3d0
	public Void RenderTweenCurrent(Int32 currentVal, Int32 maxVal, Int32 currentTargetVal, Single duration) { }
	// RVA: 0x29f65ac VA: 0x759500e5ac
	private Coroutine _CoroutineWithPage(IEnumerator coroutine) { }
	// RVA: 0x29f66a0 VA: 0x759500e6a0
	public Void .ctor() { }
}
```