# UIGuidebookPage

**Namespace:** `Torappu.UI`


## Fields

- `Image _content`

- `Image _rightArrow`

- `UIGuidebookPanel m_guidebook`


## Methods

- `Boolean Load(String, Boolean, UIGuidebookPanel)`

- `Void OnRightArrowClicked()`

- `Void Release()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIGuidebookPage : MonoBehaviour
{
	private Image _content; // 0x18
	private Image _rightArrow; // 0x20
	private UIGuidebookPanel m_guidebook; // 0x28


	// RVA: 0x217cc38 VA: 0x7594794c38
	public Boolean Load(String pageId, Boolean hasRightArrow, UIGuidebookPanel guidebook) { }
	// RVA: 0x217ceb8 VA: 0x7594794eb8
	public Void OnRightArrowClicked() { }
	// RVA: 0x217cd7c VA: 0x7594794d7c
	public Void Release() { }
	// RVA: 0x217cfd0 VA: 0x7594794fd0
	private Void OnDestroy() { }
	// RVA: 0x217cfd4 VA: 0x7594794fd4
	public Void .ctor() { }
}
```