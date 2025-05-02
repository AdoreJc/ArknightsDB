# BuildingPrefabMaker

**Namespace:** `Torappu.Building`


## Fields

- `String _outputFolder`

- `String _spineFolder`

- `VCharacter _characterProto`

- `TextAsset _characterSpecJson`

- `CharacterDB _charDB`

- `CharPatchDB _charPatchDB`

- `String _charFilter`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class BuildingPrefabMaker : ScriptableObject
{
	private const String VCHARACTER_PATH; // 0x0
	private static readonly Char[] FILTER_SEPARATORS; // 0x0
	private static readonly String[] REQUIRED_ANIMATIONS; // 0x8
	private static readonly String[] WARNING_ANIMATIONS; // 0x10
	private String _outputFolder; // 0x18
	private String _spineFolder; // 0x20
	private VCharacter _characterProto; // 0x28
	private TextAsset _characterSpecJson; // 0x30
	private CharacterDB _charDB; // 0x38
	private CharPatchDB _charPatchDB; // 0x40
	private String _charFilter; // 0x48


	// RVA: 0x3783d64 VA: 0x7595d9bd64
	public Void .ctor() { }
	// RVA: 0x3783dc4 VA: 0x7595d9bdc4
	private static Void .cctor() { }
}
```