# ChaosItem

**Namespace:** ` `


## Fields

- `GameObject _root`

- `Text _textChaosName`

- `Image _imgChaosIcon`

- `UIAtlasImage _imgChaosLevel1`

- `UIAtlasImage _imgChaosLevel2`

- `Color _colorLight`

- `Color _colorDark`


## Methods

- `Void Render(String, TransitionChaosItemData, ILoadAsset)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ChaosItem : IHotfixable
{
	private GameObject _root; // 0x10
	private Text _textChaosName; // 0x18
	private Image _imgChaosIcon; // 0x20
	private UIAtlasImage _imgChaosLevel1; // 0x28
	private UIAtlasImage _imgChaosLevel2; // 0x30
	private Color _colorLight; // 0x38
	private Color _colorDark; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2bb1488 VA: 0x75951c9488
	public Void Render(String topicId, TransitionChaosItemData chaosItemData, ILoadAsset assetLoader) { }
	// RVA: 0x2bb22d0 VA: 0x75951ca2d0
	public Void .ctor() { }
}
```