# CarvingMainBoardOutputMaterialView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `SimpleLayoutContent _materialContent`

- `Color _emptyColor`

- `Color _numColor`

- `Single _txtTweenDuration`

- `UISpineLocation _sleepLocation`

- `UISpineLocation _normalLocation`

- `UISpineLocation _happyLocation`

- `CanvasGroup _contentCanvasGroup`

- `Single _spineStateChangeDelay`

- `MaterialAdapter m_materialAdapter`

- `Boolean m_isInited`

- `Boolean m_hasMaterialChanged`

- `Tween m_pointChangeTween`

- `FadeSwitchTween m_materialContentTween`

- `Int32 m_cachedPoint`

- `BirdSpineState m_cachedWaitingState`

- `BirdSpineState m_cachedPlayingState`

- `Single m_cachedDelay`

- `Boolean m_isChanged`

- `Int32 m_cachedEnterBoardSeqNum`


## Methods

- `Void Render(CarvingMainViewModel)`

- `Void _RenderNoProcess(CarvingMainBoardOutputMaterialModel, Int32)`

- `Void _CheckMaterialChanged(List`1)`

- `Void _PlaySpineAnim()`

- `Void _PlaySpineAnimByLocation(UISpineLocation)`

- `Void _RenderProcessFrame(CarvingMainProcessModel)`

- `Void _PlayPointChange(Int32)`

- `Void _RenderText(Int32)`

- `Void _InitIfNot()`

- `Void UpdateTime(Single)`

- `Void Start()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainBoardOutputMaterialView : MonoBehaviour, IHotfixable, ITimeWatcher
{
	private const String EMPTY_DIGIT; // 0x0
	private const Int32 MAX_SCORE; // 0x0
	private SimpleLayoutContent _materialContent; // 0x18
	private List`1 _outputPoint; // 0x20
	private Color _emptyColor; // 0x28
	private Color _numColor; // 0x38
	private Single _txtTweenDuration; // 0x48
	private UISpineLocation _sleepLocation; // 0x50
	private UISpineLocation _normalLocation; // 0x60
	private UISpineLocation _happyLocation; // 0x70
	private CanvasGroup _contentCanvasGroup; // 0x80
	private Single _spineStateChangeDelay; // 0x88
	private MaterialAdapter m_materialAdapter; // 0x90
	private List`1 m_cachedMaterialItemList; // 0x98
	private Boolean m_isInited; // 0xa0
	private Boolean m_hasMaterialChanged; // 0xa1
	private Tween m_pointChangeTween; // 0xa8
	private FadeSwitchTween m_materialContentTween; // 0xb0
	private Int32 m_cachedPoint; // 0xb8
	private BirdSpineState m_cachedWaitingState; // 0xbc
	private BirdSpineState m_cachedPlayingState; // 0xc0
	private Single m_cachedDelay; // 0xc4
	private Boolean m_isChanged; // 0xc8
	private Int32 m_cachedEnterBoardSeqNum; // 0xcc
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderNoProcess; // 0x8
	private static DelegateBridge __Hotfix0__CheckMaterialChanged; // 0x10
	private static DelegateBridge __Hotfix0__PlaySpineAnim; // 0x18
	private static DelegateBridge __Hotfix0__PlaySpineAnimByLocation; // 0x20
	private static DelegateBridge __Hotfix0__RenderProcessFrame; // 0x28
	private static DelegateBridge __Hotfix0__PlayPointChange; // 0x30
	private static DelegateBridge __Hotfix0__RenderText; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x48
	private static DelegateBridge __Hotfix0_Start; // 0x50
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2d98d30 VA: 0x75953b0d30
	public Void Render(CarvingMainViewModel mainModel) { }
	// RVA: 0x2d99058 VA: 0x75953b1058
	private Void _RenderNoProcess(CarvingMainBoardOutputMaterialModel model, Int32 enterBoardSeqNum) { }
	// RVA: 0x2d99168 VA: 0x75953b1168
	private Void _CheckMaterialChanged(List`1 curMaterialList) { }
	// RVA: 0x2d9957c VA: 0x75953b157c
	private Void _PlaySpineAnim() { }
	// RVA: 0x2d9962c VA: 0x75953b162c
	private Void _PlaySpineAnimByLocation(UISpineLocation spineLocation) { }
	// RVA: 0x2d98f34 VA: 0x75953b0f34
	private Void _RenderProcessFrame(CarvingMainProcessModel model) { }
	// RVA: 0x2d9931c VA: 0x75953b131c
	private Void _PlayPointChange(Int32 point) { }
	// RVA: 0x2d99774 VA: 0x75953b1774
	private Void _RenderText(Int32 curPoint) { }
	// RVA: 0x2d98dfc VA: 0x75953b0dfc
	private Void _InitIfNot() { }
	// RVA: 0x2d99b3c VA: 0x75953b1b3c
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x2d99be0 VA: 0x75953b1be0
	private Void Start() { }
	// RVA: 0x2d99c50 VA: 0x75953b1c50
	private Void OnDestroy() { }
	// RVA: 0x2d99cc0 VA: 0x75953b1cc0
	public Void .ctor() { }
}
```