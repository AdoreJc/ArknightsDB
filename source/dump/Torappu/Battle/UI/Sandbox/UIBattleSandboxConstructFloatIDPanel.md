# UIBattleSandboxConstructFloatIDPanel

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `Canvas _rootCanvas`

- `GameObject _prefab`

- `GameObject _prefabEmpty`

- `Transform _root`

- `GridLayoutGroup _gridLayout`

- `CanvasGroup _canvasGroup`

- `Single _targetAlpha`

- `Single _fadeTime`

- `RectTransform _mask`

- `Text _hintText`

- `Text _idText`

- `IdTextSetting _inLandSetting`

- `IdTextSetting _i18nSetting`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `String _GetId()`

- `Void _InitSetting()`

- `Void Show()`

- `Void Hide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxConstructFloatIDPanel : MonoBehaviour, IHotfixable
{
	private const String ID_TEXT_FORMAT; // 0x0
	private Canvas _rootCanvas; // 0x18
	private GameObject _prefab; // 0x20
	private GameObject _prefabEmpty; // 0x28
	private Transform _root; // 0x30
	private GridLayoutGroup _gridLayout; // 0x38
	private CanvasGroup _canvasGroup; // 0x40
	private Single _targetAlpha; // 0x48
	private Single _fadeTime; // 0x4c
	private RectTransform _mask; // 0x50
	private Text _hintText; // 0x58
	private Text _idText; // 0x60
	private IdTextSetting _inLandSetting; // 0x68
	private IdTextSetting _i18nSetting; // 0x70
	private Boolean m_inited; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__GetId; // 0x8
	private static DelegateBridge __Hotfix0__InitSetting; // 0x10
	private static DelegateBridge __Hotfix0_Show; // 0x18
	private static DelegateBridge __Hotfix0_Hide; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x209a0c0 VA: 0x75946b20c0
	private Void _InitIfNot() { }
	// RVA: 0x209a5ac VA: 0x75946b25ac
	private String _GetId() { }
	// RVA: 0x209a500 VA: 0x75946b2500
	private Void _InitSetting() { }
	// RVA: 0x2095ed4 VA: 0x75946aded4
	public Void Show() { }
	// RVA: 0x2097994 VA: 0x75946af994
	public Void Hide() { }
	// RVA: 0x209a754 VA: 0x75946b2754
	public Void .ctor() { }
}
```