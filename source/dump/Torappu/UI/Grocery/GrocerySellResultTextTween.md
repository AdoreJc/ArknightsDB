# GrocerySellResultTextTween

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Text m_text`

- `GrocerySellSpacingTextItem m_specialText`

- `Boolean m_isSpecialText`

- `Tween m_tweener`

- `String m_format`

- `Int32 m_count`


## Methods

- `Void Play(Int32, Int32, Single, Single)`

- `Void Reset(Int32)`

- `Int32 <Play>b__12_0()`

- `Void <Play>b__12_1(Int32)`

- `Int32 <Play>b__12_2()`

- `Void <Play>b__12_3(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellResultTextTween : IHotfixable
{
	private const String NORMAL_FORMAT; // 0x0
	private const String NEGATIVE_FORMAT; // 0x0
	private const String POSITIVE_FORMAT; // 0x0
	private Text m_text; // 0x10
	private GrocerySellSpacingTextItem m_specialText; // 0x18
	private Boolean m_isSpecialText; // 0x20
	private Tween m_tweener; // 0x28
	private String m_format; // 0x30
	private Int32 m_count; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge _c__Hotfix1_ctor; // 0x8
	private static DelegateBridge __Hotfix0_Play; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18


	// RVA: 0x28a15b4 VA: 0x7594eb95b4
	public Void .ctor(Text text, TextFormat format) { }
	// RVA: 0x28a170c VA: 0x7594eb970c
	public Void .ctor(GrocerySellSpacingTextItem specialText) { }
	// RVA: 0x28a11ac VA: 0x7594eb91ac
	public Void Play(Int32 beginCnt, Int32 endCnt, Single duration, Single delay) { }
	// RVA: 0x28a5b20 VA: 0x7594ebdb20
	public Void Reset(Int32 endVal) { }
	// RVA: 0x28a5c24 VA: 0x7594ebdc24
	private Int32 <Play>b__12_0() { }
	// RVA: 0x28a5c2c VA: 0x7594ebdc2c
	private Void <Play>b__12_1(Int32 val) { }
	// RVA: 0x28a5c4c VA: 0x7594ebdc4c
	private Int32 <Play>b__12_2() { }
	// RVA: 0x28a5c54 VA: 0x7594ebdc54
	private Void <Play>b__12_3(Int32 val) { }
}
```