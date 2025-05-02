# AVGTutorialPointer

**Namespace:** `Torappu.AVG`


## Fields

- `Image _pointer`

- `Single _dragAnimTime`

- `Animator _pointerAnimator`

- `AnimationCurve _dragMoveCurve`

- `TrailRenderer _dragTrail`

- `Image _dragStartIcon`

- `Image _dragEndIcon`


## Methods

- `Void OnReset()`

- `Void SetClick(Vector2, Vector2)`

- `Void SetDrag(Vector2, AnchorType, Vector2, AnchorType)`

- `Void Hide()`

- `Void <SetDrag>b__9_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGTutorialPointer : MonoBehaviour
{
	private Image _pointer; // 0x18
	private Single _dragAnimTime; // 0x20
	private Animator _pointerAnimator; // 0x28
	private AnimationCurve _dragMoveCurve; // 0x30
	private TrailRenderer _dragTrail; // 0x38
	private Image _dragStartIcon; // 0x40
	private Image _dragEndIcon; // 0x48


	// RVA: 0x3eadcd4 VA: 0x75964c5cd4
	public Void OnReset() { }
	// RVA: 0x3eadd90 VA: 0x75964c5d90
	public Void SetClick(Vector2 position, Vector2 size) { }
	// RVA: 0x3eade60 VA: 0x75964c5e60
	public Void SetDrag(Vector2 startPos, AnchorType startAnchor, Vector2 endPos, AnchorType endAnchor) { }
	// RVA: 0x3eae188 VA: 0x75964c6188
	public Void Hide() { }
	// RVA: 0x3eae18c VA: 0x75964c618c
	public Void .ctor() { }
	// RVA: 0x3eae19c VA: 0x75964c619c
	private Void <SetDrag>b__9_0() { }
}
```