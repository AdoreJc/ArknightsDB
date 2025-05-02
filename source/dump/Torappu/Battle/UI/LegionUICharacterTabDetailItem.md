# LegionUICharacterTabDetailItem

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Text _levelLabel`

- `Text _descriptionLabel`

- `Image _professionImage`

- `ProfessionCategory m_currentProfession`


## Properties

- `ProfessionCategory currentProfession`


## Methods

- `ProfessionCategory get_currentProfession()`

- `Void SetData(LegionModeProfessionBuffStatus)`

- `Void ShowHighLight()`

- `Void _SetProfessionIcon(Image, ProfessionCategory, ProfessionSpritePair[])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class LegionUICharacterTabDetailItem : MonoBehaviour, IHotfixable
{
	private Text _levelLabel; // 0x18
	private Text _descriptionLabel; // 0x20
	private Image _professionImage; // 0x28
	private ProfessionSpritePair[] _professionIcons; // 0x30
	private Image[] _highLightImages; // 0x38
	private ProfessionCategory m_currentProfession; // 0x40
	private static DelegateBridge __Hotfix0_get_currentProfession; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_ShowHighLight; // 0x10
	private static DelegateBridge __Hotfix0__SetProfessionIcon; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public ProfessionCategory currentProfession { get; }

	// RVA: 0x2040074 VA: 0x7594658074
	public ProfessionCategory get_currentProfession() { }
	// RVA: 0x20400dc VA: 0x75946580dc
	public Void SetData(LegionModeProfessionBuffStatus detail) { }
	// RVA: 0x20403b0 VA: 0x75946583b0
	public Void ShowHighLight() { }
	// RVA: 0x204029c VA: 0x759465829c
	private Void _SetProfessionIcon(Image professionImage, ProfessionCategory profession, ProfessionSpritePair[] professionIcons) { }
	// RVA: 0x20404ec VA: 0x75946584ec
	public Void .ctor() { }
}
```