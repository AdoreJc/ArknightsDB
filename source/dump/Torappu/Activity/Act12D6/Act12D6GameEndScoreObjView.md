# Act12D6GameEndScoreObjView

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `AnimationWrapper _animationWrapper`

- `Text _textCount`

- `Text _textScore`

- `Single _scoreTweenDuration`

- `Single _scoreTweenDelay`

- `Color _countNormalColor`

- `Color _countZeroColor`

- `Color _scoreNormalColor`

- `Color _scoreZeroColor`

- `Boolean m_inited`

- `Int32 m_cacheCount`

- `Int32 m_cacheScore`

- `TextTweener m_scoreTweener`

- `String m_animName`


## Methods

- `Void Render(Int32, Int32)`

- `Void PlayAnim()`

- `Void ResetAnim()`

- `Void SkipAnim()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6GameEndScoreObjView : MonoBehaviour, IHotfixable
{
	private AnimationWrapper _animationWrapper; // 0x18
	private Text _textCount; // 0x20
	private Text _textScore; // 0x28
	private Single _scoreTweenDuration; // 0x30
	private Single _scoreTweenDelay; // 0x34
	private Color _countNormalColor; // 0x38
	private Color _countZeroColor; // 0x48
	private Color _scoreNormalColor; // 0x58
	private Color _scoreZeroColor; // 0x68
	private Boolean m_inited; // 0x78
	private Int32 m_cacheCount; // 0x7c
	private Int32 m_cacheScore; // 0x80
	private TextTweener m_scoreTweener; // 0x88
	private String m_animName; // 0x90
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_PlayAnim; // 0x8
	private static DelegateBridge __Hotfix0_ResetAnim; // 0x10
	private static DelegateBridge __Hotfix0_SkipAnim; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x347347c VA: 0x7595a8b47c
	public Void Render(Int32 count, Int32 score) { }
	// RVA: 0x3473e14 VA: 0x7595a8be14
	public Void PlayAnim() { }
	// RVA: 0x34740b8 VA: 0x7595a8c0b8
	public Void ResetAnim() { }
	// RVA: 0x34741c4 VA: 0x7595a8c1c4
	public Void SkipAnim() { }
	// RVA: 0x3473a24 VA: 0x7595a8ba24
	private Void _InitIfNot() { }
	// RVA: 0x34742a8 VA: 0x7595a8c2a8
	public Void .ctor() { }
}
```