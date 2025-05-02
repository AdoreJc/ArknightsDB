# RoguelikeEventImage

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Sprite m_OverrideSprite`


## Properties

- `Sprite activeSprite`


## Methods

- `Sprite get_activeSprite()`

- `Void _EditorOnlyCheckIfMatValid()`

- `Vector4 GetDrawingDimensions()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeEventImage : Image
{
	private Sprite m_OverrideSprite; // 0x188

	private Sprite activeSprite { get; }
	public override Boolean packIntoRuntimeAtlas { get; }

	// RVA: 0x2a1eec8 VA: 0x7595036ec8
	private Sprite get_activeSprite() { }
	// RVA: 0x2a1ef40 VA: 0x7595036f40
	public override Boolean get_packIntoRuntimeAtlas() { }
	// RVA: 0x2a1ef48 VA: 0x7595036f48
	private Void _EditorOnlyCheckIfMatValid() { }
	// RVA: 0x2a1f07c VA: 0x759503707c
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x2a1ffe4 VA: 0x7595037fe4
	private Vector4 GetDrawingDimensions() { }
	// RVA: 0x2a20550 VA: 0x7595038550
	public Void .ctor() { }
}
```