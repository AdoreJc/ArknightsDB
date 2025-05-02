# GroceryOrderCountTextTweener

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Text m_text`

- `Tween m_exactCountTweener`

- `Single m_dur`

- `Int32 m_cachedCount`


## Methods

- `Void Play(Int32, Boolean)`

- `Void Reset(Int32)`

- `Int32 <Play>b__5_0()`

- `Void <Play>b__5_1(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderCountTextTweener : IHotfixable
{
	private Text m_text; // 0x10
	private Tween m_exactCountTweener; // 0x18
	private Single m_dur; // 0x20
	private Int32 m_cachedCount; // 0x24
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Play; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10


	// RVA: 0x2887024 VA: 0x7594e9f024
	public Void .ctor(Text text, Single dur) { }
	// RVA: 0x28870d8 VA: 0x7594e9f0d8
	public Void Play(Int32 endCnt, Boolean isFastMode) { }
	// RVA: 0x2887328 VA: 0x7594e9f328
	public Void Reset(Int32 endCnt) { }
	// RVA: 0x28873fc VA: 0x7594e9f3fc
	private Int32 <Play>b__5_0() { }
	// RVA: 0x2887404 VA: 0x7594e9f404
	private Void <Play>b__5_1(Int32 val) { }
}
```