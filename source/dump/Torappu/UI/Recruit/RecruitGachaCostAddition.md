# RecruitGachaCostAddition

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Image _batchedTktIcon`

- `Text _batchedCount`

- `GameObject _singleTenObject`

- `GameObject _limitTenObject`

- `GameObject _combineTenObject`


## Methods

- `Void Setup(Param)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitGachaCostAddition : MonoBehaviour, IHotfixable
{
	private const Int32 COMBINE_TEN_TKT_NUM; // 0x0
	private Image _batchedTktIcon; // 0x18
	private Text _batchedCount; // 0x20
	private GameObject _singleTenObject; // 0x28
	private GameObject _limitTenObject; // 0x30
	private GameObject _combineTenObject; // 0x38
	private static DelegateBridge __Hotfix0_CheckIfSupport; // 0x0
	private static DelegateBridge __Hotfix0_Setup; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x27158bc VA: 0x7594d2d8bc
	public static Boolean CheckIfSupport(Param param) { }
	// RVA: 0x2715958 VA: 0x7594d2d958
	public Void Setup(Param param) { }
	// RVA: 0x2715aec VA: 0x7594d2daec
	public Void .ctor() { }
}
```