# UIDynamicPageHub

**Namespace:** `Torappu.UI.Page`


## Methods

- `Void set__dragPagesHere(UIPage[])`

- `Void OnBeforeSerialize()`

- `Void OnAfterDeserialize()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Page
public class UIDynamicPageHub : ScriptableObject, ISerializationCallbackReceiver
{
	private List`1 _pages; // 0x18

	private UIPage[] _dragPagesHere { get; set; }
	public List`1 pageUrls { get; }

	// RVA: 0x2c470cc VA: 0x759525f0cc
	private UIPage[] get__dragPagesHere() { }
	// RVA: 0x2c47110 VA: 0x759525f110
	private Void set__dragPagesHere(UIPage[] value) { }
	// RVA: 0x2c47114 VA: 0x759525f114
	public List`1 get_pageUrls() { }
	// RVA: 0x2c4711c VA: 0x759525f11c
	public Void OnBeforeSerialize() { }
	// RVA: 0x2c47320 VA: 0x759525f320
	public Void OnAfterDeserialize() { }
	// RVA: 0x2c47324 VA: 0x759525f324
	public Void .ctor() { }
}
```