# BattleFinishRuneItem

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Image _imageRune`

- `GameObject _imageYellow`

- `GameObject _imageBlue`

- `Text _textBuffCount`


## Methods

- `Void Render(PackedRuneData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class BattleFinishRuneItem : MonoBehaviour, IHotfixable
{
	private Image _imageRune; // 0x18
	private GameObject _imageYellow; // 0x20
	private GameObject _imageBlue; // 0x28
	private Text _textBuffCount; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x31c915c VA: 0x75957e115c
	public Void Render(PackedRuneData viewModel) { }
	// RVA: 0x31c9330 VA: 0x75957e1330
	public Void .ctor() { }
}
```