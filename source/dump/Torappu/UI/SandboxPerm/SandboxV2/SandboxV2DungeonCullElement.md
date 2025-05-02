# SandboxV2DungeonCullElement

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `CanvasGroup _alphaHandler`

- `Vector2 _boundOffsetMax`

- `Vector2 _boundOffsetMin`

- `SandboxV2DungeonCullController m_cullController`


## Methods

- `Void OnEnable()`

- `Void OnDisable()`

- `CanvasGroup GetAlphaHandler()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonCullElement : MonoBehaviour, ISandboxV2DungeonCullElement, IHotfixable
{
	private CanvasGroup _alphaHandler; // 0x18
	private Vector2 _boundOffsetMax; // 0x20
	private Vector2 _boundOffsetMin; // 0x28
	private SandboxV2DungeonCullController m_cullController; // 0x30
	private Vector3[] m_worldCullBounds; // 0x38
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0_OnDisable; // 0x8
	private static DelegateBridge __Hotfix0_GetAlphaHandler; // 0x10
	private static DelegateBridge __Hotfix0_GetWorldCullBounds; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x25122c0 VA: 0x7594b2a2c0
	private Void OnEnable() { }
	// RVA: 0x25123e8 VA: 0x7594b2a3e8
	private Void OnDisable() { }
	// RVA: 0x25124a4 VA: 0x7594b2a4a4
	public CanvasGroup GetAlphaHandler() { }
	// RVA: 0x251250c VA: 0x7594b2a50c
	public Vector3[] GetWorldCullBounds() { }
	// RVA: 0x2512680 VA: 0x7594b2a680
	public Void .ctor() { }
}
```