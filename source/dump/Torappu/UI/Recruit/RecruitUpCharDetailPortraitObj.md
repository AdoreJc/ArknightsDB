# RecruitUpCharDetailPortraitObj

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `UIAtlasImage _portraitIcon`

- `Image _backSquare`

- `Text _charName`

- `Text _textLimited`

- `GameObject _isLimitFlag`


## Methods

- `Void Render(String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitUpCharDetailPortraitObj : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _portraitIcon; // 0x18
	private Image _backSquare; // 0x20
	private Text _charName; // 0x28
	private Text _textLimited; // 0x30
	private GameObject _isLimitFlag; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x270f4a8 VA: 0x7594d274a8
	public Void Render(String charId, Boolean isLimit) { }
	// RVA: 0x2711f78 VA: 0x7594d29f78
	public Void .ctor() { }
}
```