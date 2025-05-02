# WelcomePanel

**Namespace:** ` `


## Fields

- `GameObject _pnlNormal`

- `GameObject _pnlEaten`

- `UIAtlasImage _imgBubble`

- `UIAtlasObject _atlasObject`

- `Text _textMealUsed`


## Methods

- `Void Render(Act24sideEatViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class WelcomePanel : IHotfixable
{
	private GameObject _pnlNormal; // 0x10
	private GameObject _pnlEaten; // 0x18
	private UIAtlasImage _imgBubble; // 0x20
	private UIAtlasObject _atlasObject; // 0x28
	private String[] _imgBubbleNames; // 0x30
	private Text _textMealUsed; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x329c2ac VA: 0x75958b42ac
	public Void Render(Act24sideEatViewModel viewModel, Boolean isInit) { }
	// RVA: 0x329c480 VA: 0x75958b4480
	public Void .ctor() { }
}
```