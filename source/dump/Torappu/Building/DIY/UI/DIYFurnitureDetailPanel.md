# DIYFurnitureDetailPanel

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Text _furnitureNameLabel`

- `Text _themeLabel`

- `Text _groupLabel`

- `GameObject _themeGroupPanel`

- `UsageDescGroup _lowerGroup`

- `UsageDescGroup _upperGroup`

- `Image _furnitureIcon`

- `GameObject _meetingOnlyIcon`

- `GameObject _comfortPanel`

- `Text _comfortLabel`

- `GameObjectArrayCountControl _rarityStarArray`

- `Button _okButton`

- `CanvasGroup _panelCanvasGroup`

- `Image _background`


## Methods

- `IEnumerator _LayoutCoroutine()`

- `Void Setup(IDIYItem, String, String, Int32)`

- `Void SetupTheme(FurnitureThemeViewData)`

- `Void Show()`

- `Void Hide()`

- `Void OnCloseButtonPressed()`

- `Void <Hide>b__19_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFurnitureDetailPanel : MonoBehaviour, IHotfixable
{
	private Text _furnitureNameLabel; // 0x18
	private Text _themeLabel; // 0x20
	private Text _groupLabel; // 0x28
	private GameObject _themeGroupPanel; // 0x30
	private UsageDescGroup _lowerGroup; // 0x38
	private UsageDescGroup _upperGroup; // 0x40
	private Image _furnitureIcon; // 0x48
	private GameObject _meetingOnlyIcon; // 0x50
	private GameObject _comfortPanel; // 0x58
	private Text _comfortLabel; // 0x60
	private GameObjectArrayCountControl _rarityStarArray; // 0x68
	private Button _okButton; // 0x70
	private CanvasGroup _panelCanvasGroup; // 0x78
	private Image _background; // 0x80
	private static DelegateBridge __Hotfix0__LayoutCoroutine; // 0x0
	private static DelegateBridge __Hotfix0_Setup; // 0x8
	private static DelegateBridge __Hotfix0_SetupTheme; // 0x10
	private static DelegateBridge __Hotfix0_Show; // 0x18
	private static DelegateBridge __Hotfix0_Hide; // 0x20
	private static DelegateBridge __Hotfix0_OnCloseButtonPressed; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x37fd9bc VA: 0x7595e159bc
	private IEnumerator _LayoutCoroutine() { }
	// RVA: 0x37fda90 VA: 0x7595e15a90
	public Void Setup(IDIYItem diyItem, String themeName, String groupName, Int32 count) { }
	// RVA: 0x37fe324 VA: 0x7595e16324
	public Void SetupTheme(FurnitureThemeViewData diyItemViewData) { }
	// RVA: 0x37fe6e8 VA: 0x7595e166e8
	public Void Show() { }
	// RVA: 0x37fe864 VA: 0x7595e16864
	public Void Hide() { }
	// RVA: 0x37fe9d8 VA: 0x7595e169d8
	public Void OnCloseButtonPressed() { }
	// RVA: 0x37fea40 VA: 0x7595e16a40
	public Void .ctor() { }
	// RVA: 0x37feab0 VA: 0x7595e16ab0
	private Void <Hide>b__19_0() { }
}
```