# UIMedalNotifyView

**Namespace:** `Torappu.UI`


## Fields

- `Text _textDetail`

- `Image _imgIcon`

- `Image _imgBkg`

- `Text _textName`


## Methods

- `Void _DisplayOneMedal(MedalPerData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIMedalNotifyView : UINotifyView`1
{
	private Text _textDetail; // 0x30
	private Image _imgIcon; // 0x38
	private Image _imgBkg; // 0x40
	private Text _textName; // 0x48
	private List`1 _sizeConfigs; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__DisplayOneMedal; // 0x8
	private static DelegateBridge __Hotfix0__GetMedalSizeLevel; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2273b3c VA: 0x759488bb3c
	protected override Void Render(MedalNotifyViewParam medalParam) { }
	// RVA: 0x2273d8c VA: 0x759488bd8c
	private Void _DisplayOneMedal(MedalPerData medalData) { }
	// RVA: 0x2273f50 VA: 0x759488bf50
	private static Int32 _GetMedalSizeLevel(MedalRarity rarity) { }
	// RVA: 0x2273fd0 VA: 0x759488bfd0
	public Void .ctor() { }
}
```