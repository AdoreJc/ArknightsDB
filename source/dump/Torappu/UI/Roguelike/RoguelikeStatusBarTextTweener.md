# RoguelikeStatusBarTextTweener

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Color m_normalColor`

- `Color m_increaseColor`

- `Color m_decreaseColor`

- `Text m_text`

- `Int32 m_count`

- `Int32 m_cachedCount`

- `Tween m_countTweener`

- `Tween m_colorTweener`


## Methods

- `Void Reset(Int32)`

- `Void Play(Int32)`

- `Int32 <Play>b__11_0()`

- `Void <Play>b__11_1(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeStatusBarTextTweener : IHotfixable
{
	private const Single TWEEN_DURATION; // 0x0
	private Color m_normalColor; // 0x10
	private Color m_increaseColor; // 0x20
	private Color m_decreaseColor; // 0x30
	private Text m_text; // 0x40
	private Int32 m_count; // 0x48
	private Int32 m_cachedCount; // 0x4c
	private Tween m_countTweener; // 0x50
	private Tween m_colorTweener; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0_Play; // 0x10


	// RVA: 0x2a6c174 VA: 0x7595084174
	public Void .ctor(Text text, Color normalColor, Color increaseColor, Color decreaseColor) { }
	// RVA: 0x2a6c540 VA: 0x7595084540
	public Void Reset(Int32 endCnt) { }
	// RVA: 0x2a6c614 VA: 0x7595084614
	public Void Play(Int32 endCnt) { }
	// RVA: 0x2a71284 VA: 0x7595089284
	private Int32 <Play>b__11_0() { }
	// RVA: 0x2a7128c VA: 0x759508928c
	private Void <Play>b__11_1(Int32 val) { }
}
```