# RoguelikeCommonOuterBuffLine

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `UIAnimationLocation _activeAnim`

- `String _toBuffId`

- `RoguelikeCommonOuterBuffLinePlugin _plugin`

- `Tween m_tween`

- `Boolean m_isActive`


## Methods

- `Void Init(Boolean)`

- `Void Render(Boolean, Direction, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffLine : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _activeAnim; // 0x18
	private String _toBuffId; // 0x28
	private RoguelikeCommonOuterBuffLinePlugin _plugin; // 0x30
	private Tween m_tween; // 0x38
	private Boolean m_isActive; // 0x40
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2661e24 VA: 0x7594c79e24
	public Void Init(Boolean isActive) { }
	// RVA: 0x2661f14 VA: 0x7594c79f14
	public Void Render(Boolean isActive, Direction direction, Single delay) { }
	// RVA: 0x26620fc VA: 0x7594c7a0fc
	public Void .ctor() { }
}
```