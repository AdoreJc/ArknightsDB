# RL04TempNodeUpgradeItemView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `UIAtlasImage _imgDescBg`

- `Color _colorInactiveBg`

- `Text _textDesc`

- `Color _colorInactiveDesc`

- `Color _colorActiveDesc`

- `GameObject _bgToDoGo`


## Methods

- `Void Render(RL04TempNodeUpgradeItemModel, RL04NodeUpgradeConfig, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04TempNodeUpgradeItemView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _imgDescBg; // 0x18
	private Color _colorInactiveBg; // 0x20
	private Text _textDesc; // 0x30
	private Color _colorInactiveDesc; // 0x38
	private Color _colorActiveDesc; // 0x48
	private GameObject _bgToDoGo; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2b523bc VA: 0x759516a3bc
	public Void Render(RL04TempNodeUpgradeItemModel tempNodeModel, RL04NodeUpgradeConfig styleConfig, Boolean isCurrToDo) { }
	// RVA: 0x2b5296c VA: 0x759516a96c
	public Void .ctor() { }
}
```