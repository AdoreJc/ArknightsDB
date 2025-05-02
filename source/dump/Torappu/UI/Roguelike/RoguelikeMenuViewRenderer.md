# RoguelikeMenuViewRenderer

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Getter m_getter`

- `TValue m_cachedValue`

- `Boolean m_isDirty`

- `TValue m_lastRenderValue`


## Methods

- `Boolean _Equals(TValue, TValue)`

- `Void Update()`

- `Void Render(Boolean)`

- `Void Render(Boolean, out, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuViewRenderer`1 : IRoguelikeMenuViewRenderer, IHotfixable
{
	private Action`2 m_renderAction; // 0x0
	private Getter m_getter; // 0x0
	private TValue m_cachedValue; // 0x0
	private Boolean m_isDirty; // 0x0
	private TValue m_lastRenderValue; // 0x0
	private static DelegateBridge __Hotfix0__Equals; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix1_Render; // 0x0


	// RVA: 0x VA: 0x0
	private Boolean _Equals(TValue a, TValue b) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Getter getter, Action`2 renderAction) { }
	// RVA: 0x VA: 0x0
	public Void Update() { }
	// RVA: 0x VA: 0x0
	public Void Render(Boolean fastMode) { }
	// RVA: 0x VA: 0x0
	public Void Render(Boolean fastMode, out TValue lastRenderValue, out TValue currRenderValue) { }
}
```