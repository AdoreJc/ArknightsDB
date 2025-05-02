# RL03TotemItemView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `UIScaler _scaler`

- `Image _imageIcon`

- `GameObject _locationTag`

- `GameObject _effectTag`

- `UIColorGraphic _graphic`


## Properties

- `UIColorGraphic graphic`


## Methods

- `UIColorGraphic get_graphic()`

- `Void Render(ILoadAsset, RL03TotemViewModel, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemItemView : MonoBehaviour, IHotfixable
{
	private UIScaler _scaler; // 0x18
	private Image _imageIcon; // 0x20
	private GameObject _locationTag; // 0x28
	private GameObject _effectTag; // 0x30
	private UIColorGraphic _graphic; // 0x38
	private static DelegateBridge __Hotfix0_get_graphic; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public UIColorGraphic graphic { get; }

	// RVA: 0x2b93b38 VA: 0x75951abb38
	public UIColorGraphic get_graphic() { }
	// RVA: 0x2b9359c VA: 0x75951ab59c
	public Void Render(ILoadAsset assetLoader, RL03TotemViewModel totemViewModel, Single itemScale) { }
	// RVA: 0x2b965a0 VA: 0x75951ae5a0
	public Void .ctor() { }
}
```