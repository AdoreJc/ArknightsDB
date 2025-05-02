# UISkillTagView

**Namespace:** `Torappu.UI`


## Fields

- `SkillTagType _tagType`

- `Image _colorTarget`

- `Text _contentTarget`


## Properties

- `SkillTagType tagType`


## Methods

- `SkillTagType get_tagType()`

- `Void RenderTag(SkillTagViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UISkillTagView : MonoBehaviour
{
	private SkillTagType _tagType; // 0x18
	private Image _colorTarget; // 0x20
	private Text _contentTarget; // 0x28

	public SkillTagType tagType { get; }

	// RVA: 0x2198a60 VA: 0x75947b0a60
	public SkillTagType get_tagType() { }
	// RVA: 0x21987fc VA: 0x75947b07fc
	public Void RenderTag(SkillTagViewModel tagModel) { }
	// RVA: 0x2198a68 VA: 0x75947b0a68
	public Void .ctor() { }
}
```