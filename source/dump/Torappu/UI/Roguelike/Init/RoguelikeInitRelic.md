# RoguelikeInitRelic

**Namespace:** `Torappu.UI.Roguelike.Init`


## Fields

- `Image _underTex`

- `Image _icon`

- `Text _name`

- `UIAtlasImage _nameBg`

- `Text _desc`


## Methods

- `Void Setup(Model)`

- `Color _GetBgColor(NameBgColorType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class RoguelikeInitRelic : RoguelikeInitCardBase
{
	private Image _underTex; // 0x28
	private Image _icon; // 0x30
	private Text _name; // 0x38
	private UIAtlasImage _nameBg; // 0x40
	private NameBgColor[] _nameBgColors; // 0x48
	private Text _desc; // 0x50
	private static DelegateBridge __Hotfix0_Setup; // 0x0
	private static DelegateBridge __Hotfix0__GetBgColor; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2b860dc VA: 0x759519e0dc
	public Void Setup(Model model) { }
	// RVA: 0x2b88f30 VA: 0x75951a0f30
	private Color _GetBgColor(NameBgColorType clrType) { }
	// RVA: 0x2b89030 VA: 0x75951a1030
	public Void .ctor() { }
}
```