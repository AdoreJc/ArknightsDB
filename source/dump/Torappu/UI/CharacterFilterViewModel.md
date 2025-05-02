# CharacterFilterViewModel

**Namespace:** `Torappu.UI`


## Fields

- `Boolean isAll`


## Methods

- `Boolean IsValid(CharacterCardViewModel)`

- `Boolean IsValid(RoguelikeCharCardViewModel)`

- `Boolean IsValid(HomeSecretaryCardViewModel)`

- `Void Set(CharacterFilterViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CharacterFilterViewModel
{
	public Boolean isAll; // 0x10
	private List`1 m_elements; // 0x18

	public List`1 elements { get; }

	// RVA: 0x21207b8 VA: 0x75947387b8
	public Boolean IsValid(CharacterCardViewModel viewModel) { }
	// RVA: 0x2123568 VA: 0x759473b568
	public Boolean IsValid(RoguelikeCharCardViewModel viewModel) { }
	// RVA: 0x2123644 VA: 0x759473b644
	public Boolean IsValid(HomeSecretaryCardViewModel viewModel) { }
	// RVA: 0x2123710 VA: 0x759473b710
	public List`1 get_elements() { }
	// RVA: 0x2117e34 VA: 0x759472fe34
	public Void Set(CharacterFilterViewModel filter) { }
	// RVA: 0x2123718 VA: 0x759473b718
	public static CharacterFilterViewModel CreateFromProfessionMask(ProfessionCategory professionMask) { }
	// RVA: 0x212129c VA: 0x759473929c
	public Void .ctor() { }
}
```