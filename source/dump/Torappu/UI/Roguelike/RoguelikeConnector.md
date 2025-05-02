# RoguelikeConnector

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Boolean _useClipColor`

- `Single _clipRatio`

- `Color _clipColor`


## Properties

- `Boolean useClipColor`

- `Color clipColor`


## Methods

- `Boolean get_useClipColor()`

- `Void set_useClipColor(Boolean)`

- `Color get_clipColor()`

- `Void set_clipColor(Color)`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeConnector : Image, IHotfixable
{
	private Boolean _useClipColor; // 0x188
	private Single _clipRatio; // 0x18c
	private Color _clipColor; // 0x190
	private static DelegateBridge __Hotfix0_get_useClipColor; // 0x0
	private static DelegateBridge __Hotfix0_set_useClipColor; // 0x8
	private static DelegateBridge __Hotfix0_get_clipColor; // 0x10
	private static DelegateBridge __Hotfix0_set_clipColor; // 0x18
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean useClipColor { get; set; }
	public Color clipColor { get; set; }

	// RVA: 0x2a1a240 VA: 0x7595032240
	public Boolean get_useClipColor() { }
	// RVA: 0x2a1a2a8 VA: 0x75950322a8
	public Void set_useClipColor(Boolean value) { }
	// RVA: 0x2a1a328 VA: 0x7595032328
	public Color get_clipColor() { }
	// RVA: 0x2a1a398 VA: 0x7595032398
	public Void set_clipColor(Color value) { }
	// RVA: 0x2a1a444 VA: 0x7595032444
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x2a1b36c VA: 0x759503336c
	public Void .ctor() { }
	// RVA: 0x2a1b408 VA: 0x7595033408
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```