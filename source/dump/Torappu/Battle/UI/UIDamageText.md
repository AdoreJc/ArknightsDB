# UIDamageText

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Vector2 _upOffset`

- `Vector2 _downOffset`

- `Single _fontSizeScale`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIDamageText : UINumericText
{
	private const Single CRITICAL_FONT_SIZE_SCALE; // 0x0
	private Vector2 _upOffset; // 0x38
	private Vector2 _downOffset; // 0x40
	private Single _fontSizeScale; // 0x48
	private static DelegateBridge __Hotfix0_get_format; // 0x0
	private static DelegateBridge __Hotfix0_SetTweens; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	protected override String format { get; }

	// RVA: 0x207ccb0 VA: 0x7594694cb0
	protected override String get_format() { }
	// RVA: 0x207cd2c VA: 0x7594694d2c
	protected override Void SetTweens(Single duration) { }
	// RVA: 0x207cfb8 VA: 0x7594694fb8
	public Void .ctor() { }
}
```