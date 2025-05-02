# SiracusaCharTaskRingItemView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `Text _textRingDesc`

- `GameObject _splitLineGo`

- `UIAtlasImage _taskRingLine`

- `LayoutElement _taskListLayout`

- `CanvasGroup _taskListAlphaHandler`

- `Single _expandDuration`

- `SiracusaCharTaskListView _conditionTaskListViewPrefab`

- `SiracusaCharTaskListView _linearTaskListViewPrefab`

- `UIAtlasImage _imgStatus`

- `UIAtlasObject _iconStatusAtlas`

- `String _iconCompleteName`

- `String _iconDoingName`

- `String _iconLockedName`

- `Int32 m_index`

- `SiracusaCharTaskListView m_listView`

- `Boolean m_prevIsLinear`

- `Single m_listHeight`

- `FadeTranslationSwitchTween m_switchTween`

- `Boolean m_hasInited`


## Methods

- `Void set_onRingSelect(Action`1)`

- `Void set_onTaskClick(Action`2)`

- `Void Render(Int32, SiracusaCharTaskRingModel, Boolean, Boolean)`

- `Void _InitIfNot()`

- `Void _CreateListViewIfNeed(Boolean)`

- `Void _UpdateStatusIcon(TaskRingStatus, Boolean)`

- `Void EventOnSelectRing()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharTaskRingItemView : MonoBehaviour, IHotfixable
{
	private Text _textRingDesc; // 0x18
	private GameObject _splitLineGo; // 0x20
	private UIAtlasImage _taskRingLine; // 0x28
	private LayoutElement _taskListLayout; // 0x30
	private CanvasGroup _taskListAlphaHandler; // 0x38
	private Single _expandDuration; // 0x40
	private SiracusaCharTaskListView _conditionTaskListViewPrefab; // 0x48
	private SiracusaCharTaskListView _linearTaskListViewPrefab; // 0x50
	private UIAtlasImage _imgStatus; // 0x58
	private UIAtlasObject _iconStatusAtlas; // 0x60
	private String _iconCompleteName; // 0x68
	private String _iconDoingName; // 0x70
	private String _iconLockedName; // 0x78
	private Int32 m_index; // 0x80
	private SiracusaCharTaskListView m_listView; // 0x88
	private Boolean m_prevIsLinear; // 0x90
	private Single m_listHeight; // 0x94
	private FadeTranslationSwitchTween m_switchTween; // 0x98
	private Boolean m_hasInited; // 0xa0
	private Action`1 <onRingSelect>k__BackingField; // 0xa8
	private Action`2 <onTaskClick>k__BackingField; // 0xb0
	private static DelegateBridge __Hotfix0_get_onRingSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onRingSelect; // 0x8
	private static DelegateBridge __Hotfix0_get_onTaskClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onTaskClick; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__CreateListViewIfNeed; // 0x30
	private static DelegateBridge __Hotfix0__UpdateStatusIcon; // 0x38
	private static DelegateBridge __Hotfix0_EventOnSelectRing; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Action`1 onRingSelect { get; set; }
	private Action`2 onTaskClick { get; set; }

	// RVA: 0x23ea2fc VA: 0x7594a022fc
	private Action`1 get_onRingSelect() { }
	// RVA: 0x23e8fb4 VA: 0x7594a00fb4
	public Void set_onRingSelect(Action`1 value) { }
	// RVA: 0x23ea364 VA: 0x7594a02364
	private Action`2 get_onTaskClick() { }
	// RVA: 0x23e9038 VA: 0x7594a01038
	public Void set_onTaskClick(Action`2 value) { }
	// RVA: 0x23e90bc VA: 0x7594a010bc
	public Void Render(Int32 index, SiracusaCharTaskRingModel taskRingModel, Boolean isSelect, Boolean isEnd) { }
	// RVA: 0x23ea3cc VA: 0x7594a023cc
	private Void _InitIfNot() { }
	// RVA: 0x23ea5a0 VA: 0x7594a025a0
	private Void _CreateListViewIfNeed(Boolean isLinear) { }
	// RVA: 0x23ea49c VA: 0x7594a0249c
	private Void _UpdateStatusIcon(TaskRingStatus ringStatus, Boolean isUnlock) { }
	// RVA: 0x23ea7d8 VA: 0x7594a027d8
	public Void EventOnSelectRing() { }
	// RVA: 0x23ea878 VA: 0x7594a02878
	public Void .ctor() { }
}
```