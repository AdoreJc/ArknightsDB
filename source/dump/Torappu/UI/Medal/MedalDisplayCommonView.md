# MedalDisplayCommonView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Text _medalGroupName`

- `Text _medalDescription`

- `Text _medalCount`

- `Text _medalAvailCount`


## Methods

- `Void Render(MedalDisplayViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalDisplayCommonView : MonoBehaviour, IHotfixable
{
	private Text _medalGroupName; // 0x18
	private Text _medalDescription; // 0x20
	private Text _medalCount; // 0x28
	private Text _medalAvailCount; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x27a8944 VA: 0x7594dc0944
	public Void Render(MedalDisplayViewModel viewModel) { }
	// RVA: 0x27a8b20 VA: 0x7594dc0b20
	public Void .ctor() { }
}
```