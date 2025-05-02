# RL03MenuVCChaosItem

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `Image _icon`

- `Text _name`

- `Text _desc`


## Methods

- `Void Render(ChaosItemModel, ILoadAsset, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03MenuVCChaosItem : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private Text _name; // 0x20
	private Text _desc; // 0x28
	private GameObject[] _levelIcons; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2ba07a4 VA: 0x75951b87a4
	public Void Render(ChaosItemModel itemModel, ILoadAsset loader, String topicId) { }
	// RVA: 0x2ba0974 VA: 0x75951b8974
	public Void .ctor() { }
}
```