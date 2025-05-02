# RoguelikeCommonOuterBuffNodeSocket

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `UIAnimationLocation _activeAnim`

- `Single _animLength`

- `Tween m_tween`

- `Boolean m_isActive`


## Methods

- `Void Init(Boolean)`

- `Void Render(Boolean, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffNodeSocket : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _activeAnim; // 0x18
	private List`1 _fromLines; // 0x28
	private List`1 _lines; // 0x30
	private Single _animLength; // 0x38
	private Tween m_tween; // 0x40
	private Boolean m_isActive; // 0x48
	private static DelegateBridge __Hotfix0_get_fromLines; // 0x0
	private static DelegateBridge __Hotfix0_get_lines; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public List`1 fromLines { get; }
	public List`1 lines { get; }

	// RVA: 0x265e60c VA: 0x7594c7660c
	public List`1 get_fromLines() { }
	// RVA: 0x265e5a4 VA: 0x7594c765a4
	public List`1 get_lines() { }
	// RVA: 0x26622dc VA: 0x7594c7a2dc
	public Void Init(Boolean isActive) { }
	// RVA: 0x2662430 VA: 0x7594c7a430
	public Void Render(Boolean isActive, Single delay) { }
	// RVA: 0x26626b0 VA: 0x7594c7a6b0
	public Void .ctor() { }
}
```