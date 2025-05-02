# UniEquipShowView

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `GameObject _panelEquipBack`

- `Text _equipName`

- `Text _equipDesc`

- `AnimationWrapper _animationWrapper`

- `Transform _imgContainer`

- `UniEquipImgHolder _imgHolder`

- `Transform _typeContainer`

- `UICommonEquipTypeIcon _typeIcon`

- `String NORM_ANIM`

- `String UNLOCK_ANIM`

- `Boolean m_isUnlockShow`

- `Boolean m_isInited`

- `UniEquipImgHolder m_imgHolder`

- `UICommonEquipTypeIcon m_typeIcon`


## Methods

- `Void _InitIfNot()`

- `Void Render(UniEquipData, String, Boolean)`

- `Void ApplyAnim()`

- `Void ResetAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipShowView : MonoBehaviour, IHotfixable
{
	private GameObject _panelEquipBack; // 0x18
	private Text _equipName; // 0x20
	private Text _equipDesc; // 0x28
	private AnimationWrapper _animationWrapper; // 0x30
	private Transform _imgContainer; // 0x38
	private UniEquipImgHolder _imgHolder; // 0x40
	private Transform _typeContainer; // 0x48
	private UICommonEquipTypeIcon _typeIcon; // 0x50
	private String NORM_ANIM; // 0x58
	private String UNLOCK_ANIM; // 0x60
	private Boolean m_isUnlockShow; // 0x68
	private Boolean m_isInited; // 0x69
	private UniEquipImgHolder m_imgHolder; // 0x70
	private UICommonEquipTypeIcon m_typeIcon; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_ApplyAnim; // 0x10
	private static DelegateBridge __Hotfix0_ResetAnim; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x230ed48 VA: 0x7594926d48
	private Void _InitIfNot() { }
	// RVA: 0x230ee60 VA: 0x7594926e60
	public Void Render(UniEquipData uniEquipData, String subProfessionId, Boolean isUnlockShow) { }
	// RVA: 0x230efe0 VA: 0x7594926fe0
	public Void ApplyAnim() { }
	// RVA: 0x230f0a4 VA: 0x75949270a4
	public Void ResetAnim() { }
	// RVA: 0x230f170 VA: 0x7594927170
	public Void .ctor() { }
}
```