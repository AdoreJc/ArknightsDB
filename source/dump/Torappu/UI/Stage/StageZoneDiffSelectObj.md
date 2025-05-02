# StageZoneDiffSelectObj

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIDiffGroupEvent selectDiffAction`

- `Image _iconImg`

- `Text _longName`

- `Text _shortName`

- `AnimationWrapper _animWrapper`

- `GameObject _isLockPart`

- `Button _button`

- `UIColorGraphic _colorGraphic`

- `Color _lockedColor`

- `UIAtlasImage _backImage`

- `UIAtlasObject _atlasHub`

- `String _commonBack`

- `String _toughBack`

- `StageDiffGroup m_diffGroup`

- `Boolean m_cacheUnlock`

- `Single m_state`

- `Tween m_cacheTween`


## Methods

- `Void Render(StageDiffGroup, Boolean)`

- `Void OnClick()`

- `Void SetSelect(StageDiffGroup)`

- `Single <SetSelect>b__20_0()`

- `Void <SetSelect>b__20_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneDiffSelectObj : MonoBehaviour, IHotfixable
{
	public UIDiffGroupEvent selectDiffAction; // 0x18
	private Image _iconImg; // 0x20
	private Text _longName; // 0x28
	private Text _shortName; // 0x30
	private AnimationWrapper _animWrapper; // 0x38
	private GameObject _isLockPart; // 0x40
	private Button _button; // 0x48
	private UIColorGraphic _colorGraphic; // 0x50
	private Color _lockedColor; // 0x58
	private UIAtlasImage _backImage; // 0x68
	private UIAtlasObject _atlasHub; // 0x70
	private String _commonBack; // 0x78
	private String _toughBack; // 0x80
	private StageDiffGroup m_diffGroup; // 0x88
	private Boolean m_cacheUnlock; // 0x8c
	private const String PARAM_ANIM; // 0x0
	private Single m_state; // 0x90
	private Tween m_cacheTween; // 0x98
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0_SetSelect; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f8e638 VA: 0x75955a6638
	public Void Render(StageDiffGroup diffGroup, Boolean isUnlock) { }
	// RVA: 0x2f8ee6c VA: 0x75955a6e6c
	public Void OnClick() { }
	// RVA: 0x2f8ecc8 VA: 0x75955a6cc8
	public Void SetSelect(StageDiffGroup diffGroup) { }
	// RVA: 0x2f8ef4c VA: 0x75955a6f4c
	public Void .ctor() { }
	// RVA: 0x2f8efbc VA: 0x75955a6fbc
	private Single <SetSelect>b__20_0() { }
	// RVA: 0x2f8efc4 VA: 0x75955a6fc4
	private Void <SetSelect>b__20_1(Single val) { }
}
```