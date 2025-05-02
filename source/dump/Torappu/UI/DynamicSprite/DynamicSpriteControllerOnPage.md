# DynamicSpriteControllerOnPage

**Namespace:** `Torappu.UI.DynamicSprite`


## Fields

- `UIPageListener m_pageListener`


## Methods

- `Void _OnPageReady()`

- `Void _OnPageNotFound()`

- `Void OnPrefabUpdated()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DynamicSprite
public class DynamicSpriteControllerOnPage : MonoBehaviour, IOnPrefabUpdated
{
	private DynamicSpriteLoader[] _loaders; // 0x18
	private UIPageListener m_pageListener; // 0x20


	// RVA: 0x2c460a0 VA: 0x759525e0a0
	private Void _OnPageReady() { }
	// RVA: 0x2c46230 VA: 0x759525e230
	private Void _OnPageNotFound() { }
	// RVA: 0x2c46354 VA: 0x759525e354
	protected virtual Void Start() { }
	// RVA: 0x2c46444 VA: 0x759525e444
	public Void OnPrefabUpdated() { }
	// RVA: 0x2c46448 VA: 0x759525e448
	public Void .ctor() { }
}
```