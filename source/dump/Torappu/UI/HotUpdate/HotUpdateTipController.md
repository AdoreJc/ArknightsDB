# HotUpdateTipController

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `Text _titleText`

- `Text _descriptionText`

- `Image _backgroundImage`

- `WorldViewTip m_lastTip`

- `DirectAssetLoader m_assetLoader`


## Methods

- `Void PickNewTip(Boolean)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdateTipController : MonoBehaviour
{
	private Text _titleText; // 0x18
	private Text _descriptionText; // 0x20
	private Image _backgroundImage; // 0x28
	private WorldViewTip m_lastTip; // 0x30
	private DirectAssetLoader m_assetLoader; // 0x38


	// RVA: 0x27bc72c VA: 0x7594dd472c
	public Void PickNewTip(Boolean isInit) { }
	// RVA: 0x27bc90c VA: 0x7594dd490c
	private Void OnDestroy() { }
	// RVA: 0x27bc92c VA: 0x7594dd492c
	public Void .ctor() { }
}
```