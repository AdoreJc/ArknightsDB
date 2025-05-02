# MedalCommonItemNotGetView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Text _medalName`

- `Image _icon`

- `GameObject _rewardFlag`


## Methods

- `Void Render(MedalCommonViewModel, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalCommonItemNotGetView : MonoBehaviour, IHotfixable
{
	private Text _medalName; // 0x18
	private Image _icon; // 0x20
	private GameObject _rewardFlag; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2798e24 VA: 0x7594db0e24
	public Void Render(MedalCommonViewModel viewModel, String pageName) { }
	// RVA: 0x2799024 VA: 0x7594db1024
	public Void .ctor() { }
}
```