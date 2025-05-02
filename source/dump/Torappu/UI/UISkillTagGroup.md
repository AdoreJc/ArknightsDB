# UISkillTagGroup

**Namespace:** `Torappu.UI`


## Fields

- `Transform _tagContainer`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(List`1)`

- `Void _RespawnTagViews()`

- `UISkillTagView _LoadTag(SkillTagType, Int32)`

- `Void _HideIdleViews()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UISkillTagGroup : MonoBehaviour
{
	private GameObject[] _tagPrefabs; // 0x18
	private Transform _tagContainer; // 0x20
	private List`1 m_tagCache; // 0x28
	private List`1 m_spareTagViewPool; // 0x30
	private Boolean m_isInited; // 0x38


	// RVA: 0x21980b0 VA: 0x75947b00b0
	private Void _InitIfNot() { }
	// RVA: 0x21982a0 VA: 0x75947b02a0
	public Void Render(List`1 tags) { }
	// RVA: 0x2198494 VA: 0x75947b0494
	private Void _RespawnTagViews() { }
	// RVA: 0x2198528 VA: 0x75947b0528
	private UISkillTagView _LoadTag(SkillTagType type, Int32 index) { }
	// RVA: 0x21988e4 VA: 0x75947b08e4
	private Void _HideIdleViews() { }
	// RVA: 0x219898c VA: 0x75947b098c
	private static Void _AdjustSiblingIndex(Transform transform, Int32 index) { }
	// RVA: 0x21989d8 VA: 0x75947b09d8
	public Void .ctor() { }
}
```