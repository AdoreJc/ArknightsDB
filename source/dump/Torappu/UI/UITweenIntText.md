# UITweenIntText

**Namespace:** `Torappu.UI`


## Fields

- `Text m_text`

- `Int32 m_currNum`

- `Tween m_cachedTween`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UITweenIntText : BasicTween`1, IHotfixable
{
	private Text m_text; // 0x48
	private Int32 m_currNum; // 0x50
	private Tween m_cachedTween; // 0x58
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetTweenValue; // 0x8
	private static DelegateBridge __Hotfix0_SetTweenValue; // 0x10
	private static DelegateBridge __Hotfix0_ConstructTweener; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x217791c VA: 0x759478f91c
	protected override Void OnInit() { }
	// RVA: 0x2177a54 VA: 0x759478fa54
	protected override Int32 GetTweenValue() { }
	// RVA: 0x2177abc VA: 0x759478fabc
	protected override Void SetTweenValue(Int32 val) { }
	// RVA: 0x2177bd4 VA: 0x759478fbd4
	protected override Tweener ConstructTweener(Int32 fromValue, Int32 toValue, Single duration) { }
	// RVA: 0x2177d28 VA: 0x759478fd28
	public Void .ctor() { }
}
```