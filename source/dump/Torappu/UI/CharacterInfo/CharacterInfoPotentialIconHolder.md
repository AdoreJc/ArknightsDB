# CharacterInfoPotentialIconHolder

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Image _imgPotentialIcon`

- `CanvasGroup _alphaHandler`


## Properties

- `CanvasGroup alphaHandler`


## Methods

- `CanvasGroup get_alphaHandler()`

- `Void Render(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoPotentialIconHolder : MonoBehaviour, IHotfixable
{
	private Image _imgPotentialIcon; // 0x18
	private CanvasGroup _alphaHandler; // 0x20
	private static DelegateBridge __Hotfix0_get_alphaHandler; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public CanvasGroup alphaHandler { get; }

	// RVA: 0x2d7d854 VA: 0x7595395854
	public CanvasGroup get_alphaHandler() { }
	// RVA: 0x2d7d8bc VA: 0x75953958bc
	public Void Render(Int32 rank) { }
	// RVA: 0x2d7d98c VA: 0x759539598c
	public Void .ctor() { }
}
```