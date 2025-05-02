# Rl01OuterBuffSkillTreeLineSegment

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `Rl01OuterBuffSkillTreeLineType _lineType`

- `Image _lineImg`

- `Int32 _length`

- `Boolean m_cachedShow`

- `Tween m_tween`


## Properties

- `Rl01OuterBuffSkillTreeLineType lineType`

- `Image lineImg`

- `Int32 length`


## Methods

- `Rl01OuterBuffSkillTreeLineType get_lineType()`

- `Void set_lineType(Rl01OuterBuffSkillTreeLineType)`

- `Image get_lineImg()`

- `Void set_lineImg(Image)`

- `Int32 get_length()`

- `Void set_length(Int32)`

- `Single SetShow(Boolean, Single, Boolean)`

- `Tween _GenerateTween(Single)`

- `Single GetDelay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class Rl01OuterBuffSkillTreeLineSegment : MonoBehaviour, IHotfixable
{
	private const Int32 LINE_WIDTH; // 0x0
	private const Single LINE_VELOCITY; // 0x0
	private const Single POINT_LIGHT_DURATION; // 0x0
	private Rl01OuterBuffSkillTreeLineType _lineType; // 0x18
	private Image _lineImg; // 0x20
	private Int32 _length; // 0x28
	private Boolean m_cachedShow; // 0x2c
	private Tween m_tween; // 0x30
	private static DelegateBridge __Hotfix0_get_lineType; // 0x0
	private static DelegateBridge __Hotfix0_set_lineType; // 0x8
	private static DelegateBridge __Hotfix0_get_lineImg; // 0x10
	private static DelegateBridge __Hotfix0_set_lineImg; // 0x18
	private static DelegateBridge __Hotfix0_get_length; // 0x20
	private static DelegateBridge __Hotfix0_set_length; // 0x28
	private static DelegateBridge __Hotfix0_SetShow; // 0x30
	private static DelegateBridge __Hotfix0__GenerateTween; // 0x38
	private static DelegateBridge __Hotfix0_GetDelay; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Rl01OuterBuffSkillTreeLineType lineType { get; set; }
	private Image lineImg { get; set; }
	private Int32 length { get; set; }

	// RVA: 0x26cf400 VA: 0x7594ce7400
	private Rl01OuterBuffSkillTreeLineType get_lineType() { }
	// RVA: 0x26cf468 VA: 0x7594ce7468
	public Void set_lineType(Rl01OuterBuffSkillTreeLineType value) { }
	// RVA: 0x26cf4e4 VA: 0x7594ce74e4
	private Image get_lineImg() { }
	// RVA: 0x26cf54c VA: 0x7594ce754c
	public Void set_lineImg(Image value) { }
	// RVA: 0x26cf5d0 VA: 0x7594ce75d0
	private Int32 get_length() { }
	// RVA: 0x26cf638 VA: 0x7594ce7638
	public Void set_length(Int32 value) { }
	// RVA: 0x26cf6b4 VA: 0x7594ce76b4
	public Single SetShow(Boolean show, Single delay, Boolean isInit) { }
	// RVA: 0x26cf90c VA: 0x7594ce790c
	private Tween _GenerateTween(Single delay) { }
	// RVA: 0x26cfaa8 VA: 0x7594ce7aa8
	public Single GetDelay() { }
	// RVA: 0x26cfb3c VA: 0x7594ce7b3c
	public Void .ctor() { }
}
```