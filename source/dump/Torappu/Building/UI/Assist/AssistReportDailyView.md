# AssistReportDailyView

**Namespace:** `Torappu.Building.UI.Assist`


## Fields

- `AssistReportManuView _manuView`

- `AssistReportShopView _shopView`

- `AssistReportFavorView _favorView`

- `Text _timeText`

- `GameObject _nullPart`

- `GameObject _firstDayNullPart`

- `GameObject _reportObjPart`


## Methods

- `Void Render(BuildingDailyReport)`

- `Void RenderNull(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Assist
public class AssistReportDailyView : MonoBehaviour, IHotfixable
{
	private AssistReportManuView _manuView; // 0x18
	private AssistReportShopView _shopView; // 0x20
	private AssistReportFavorView _favorView; // 0x28
	private Text _timeText; // 0x30
	private GameObject _nullPart; // 0x38
	private GameObject _firstDayNullPart; // 0x40
	private GameObject _reportObjPart; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_RenderNull; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3e31af0 VA: 0x7596449af0
	public Void Render(BuildingDailyReport report) { }
	// RVA: 0x3e31d0c VA: 0x7596449d0c
	public Void RenderNull(Int32 index) { }
	// RVA: 0x3e345a0 VA: 0x759644c5a0
	public Void .ctor() { }
}
```