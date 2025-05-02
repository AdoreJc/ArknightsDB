# UILegionDangerLevel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Text _levelText`

- `Text _levelTextBlack`

- `GameObject _objMax`

- `Slider _leftSlider`

- `Slider _rightSlider`

- `UILegionDangerLevelEffectHolder _effectHolder`


## Methods

- `Void SetData(Single, Int32)`

- `Void UpdateData(Int32, Int32, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UILegionDangerLevel : MonoBehaviour, IHotfixable
{
	private Text _levelText; // 0x18
	private Text _levelTextBlack; // 0x20
	private GameObject _objMax; // 0x28
	private Slider _leftSlider; // 0x30
	private Slider _rightSlider; // 0x38
	private UILegionDangerLevelEffectHolder _effectHolder; // 0x40
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2080720 VA: 0x7594698720
	public Void SetData(Single interval, Int32 initLevel) { }
	// RVA: 0x20808d0 VA: 0x75946988d0
	public Void UpdateData(Int32 dangerLevel, Int32 maxLevel, Single progressToNextLevel) { }
	// RVA: 0x2080b2c VA: 0x7594698b2c
	public Void .ctor() { }
}
```