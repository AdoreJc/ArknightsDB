# UIMedalDIYFrame

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Single _unit`

- `String _frameId`

- `Image _imgMesh`

- `Boolean _isPredefinedFrame`

- `RectTransform m_rectTrans`


## Properties

- `RectTransform rectTrans`

- `String frameId`


## Methods

- `RectTransform get_rectTrans()`

- `String get_frameId()`

- `Void Init(UIPage, Boolean)`

- `HexPoint AlignToHex(RectTransform)`

- `Vector2 ConvertToAnchoredPos(HexPoint)`

- `Single GetUnit()`

- `PosValidateResult ValidateMedalPosition(MedalPosInfo, List`1)`

- `Boolean ValidateMedalPositions(List`1)`

- `Void PopulateGraphics(List`1)`

- `Vector2 _GetCrossPos(RectTransform)`

- `Void OnPrefabUpdated()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class UIMedalDIYFrame : MonoBehaviour, IHotfixable, IOnPrefabUpdated
{
	private List`1 _bound; // 0x18
	private Single _unit; // 0x20
	private String _frameId; // 0x28
	private Image _imgMesh; // 0x30
	private Boolean _isPredefinedFrame; // 0x38
	private RectTransform m_rectTrans; // 0x40
	private static DelegateBridge __Hotfix0_get_rectTrans; // 0x0
	private static DelegateBridge __Hotfix0_get_frameId; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_AlignToHex; // 0x18
	private static DelegateBridge __Hotfix0_ConvertToAnchoredPos; // 0x20
	private static DelegateBridge __Hotfix0_GetBound; // 0x28
	private static DelegateBridge __Hotfix0_GetUnit; // 0x30
	private static DelegateBridge __Hotfix0_ValidateMedalPosition; // 0x38
	private static DelegateBridge __Hotfix0_ValidateMedalPositions; // 0x40
	private static DelegateBridge __Hotfix0_PopulateGraphics; // 0x48
	private static DelegateBridge __Hotfix0__GetCrossPos; // 0x50
	private static DelegateBridge __Hotfix0__MedalSizeToUnit; // 0x58
	private static DelegateBridge __Hotfix0_Start; // 0x60
	private static DelegateBridge __Hotfix0_OnPrefabUpdated; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public RectTransform rectTrans { get; }
	public String frameId { get; }

	// RVA: 0x2765b28 VA: 0x7594d7db28
	public RectTransform get_rectTrans() { }
	// RVA: 0x2765c28 VA: 0x7594d7dc28
	public String get_frameId() { }
	// RVA: 0x2765c90 VA: 0x7594d7dc90
	public Void Init(UIPage page, Boolean usePool) { }
	// RVA: 0x2765d50 VA: 0x7594d7dd50
	public HexPoint AlignToHex(RectTransform child) { }
	// RVA: 0x2766078 VA: 0x7594d7e078
	public Vector2 ConvertToAnchoredPos(HexPoint point) { }
	// RVA: 0x2766180 VA: 0x7594d7e180
	public List`1 GetBound() { }
	// RVA: 0x2766118 VA: 0x7594d7e118
	public Single GetUnit() { }
	// RVA: 0x27661e8 VA: 0x7594d7e1e8
	public PosValidateResult ValidateMedalPosition(MedalPosInfo target, List`1 others) { }
	// RVA: 0x276647c VA: 0x7594d7e47c
	public Boolean ValidateMedalPositions(List`1 medalList) { }
	// RVA: 0x27665fc VA: 0x7594d7e5fc
	public Void PopulateGraphics(List`1 list) { }
	// RVA: 0x2765f94 VA: 0x7594d7df94
	private Vector2 _GetCrossPos(RectTransform child) { }
	// RVA: 0x2766400 VA: 0x7594d7e400
	private static Int32 _MedalSizeToUnit(MedalSize size) { }
	// RVA: 0x2766700 VA: 0x7594d7e700
	protected virtual Void Start() { }
	// RVA: 0x2766764 VA: 0x7594d7e764
	public Void OnPrefabUpdated() { }
	// RVA: 0x27667c8 VA: 0x7594d7e7c8
	public Void .ctor() { }
}
```