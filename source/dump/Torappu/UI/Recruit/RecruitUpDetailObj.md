# RecruitUpDetailObj

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Image _starSprite`

- `Transform _container`

- `RecruitCharDetailObj _charObj`

- `RecruitUpCharDetailPortraitObj _portraitObj`

- `Text _title`

- `GameObject _endLine`

- `GameObject _security6`

- `GameObject _security5`

- `GameObject _textDetail`

- `Text _textDetailLabel`


## Methods

- `Void Render(GachaPerChar, Boolean, Boolean, List`1)`

- `Void Render(GachaPerAvail, Boolean, Options, Boolean, String)`

- `Void RenderWeightUpChar(List`1, Single)`

- `Void _Render6StarHint(Boolean, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitUpDetailObj : MonoBehaviour, IHotfixable
{
	private Image _starSprite; // 0x18
	private Transform _container; // 0x20
	private RecruitCharDetailObj _charObj; // 0x28
	private RecruitUpCharDetailPortraitObj _portraitObj; // 0x30
	private Text _title; // 0x38
	private GameObject _endLine; // 0x40
	private GameObject _security6; // 0x48
	private GameObject _security5; // 0x50
	private GameObject _textDetail; // 0x58
	private Text _textDetailLabel; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix1_Render; // 0x8
	private static DelegateBridge __Hotfix0_RenderWeightUpChar; // 0x10
	private static DelegateBridge __Hotfix0__Render6StarHint; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2711fe8 VA: 0x7594d29fe8
	public Void Render(GachaPerChar upCharList, Boolean isEnd, Boolean isPortrait, List`1 limitList) { }
	// RVA: 0x270fea4 VA: 0x7594d27ea4
	public Void Render(GachaPerAvail perObj, Boolean isEnd, Options option, Boolean isPortrait, String recruit6StarHint) { }
	// RVA: 0x2712564 VA: 0x7594d2a564
	public Void RenderWeightUpChar(List`1 weightUpCharList, Single percent) { }
	// RVA: 0x2712444 VA: 0x7594d2a444
	private Void _Render6StarHint(Boolean showFlag, String recruit6StarHint) { }
	// RVA: 0x27129f4 VA: 0x7594d2a9f4
	public Void .ctor() { }
}
```