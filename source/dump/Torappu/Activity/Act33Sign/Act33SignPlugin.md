# Act33SignPlugin

**Namespace:** `Torappu.Activity.Act33Sign`


## Fields

- `Act33SignRedpackDetailView _detailView`

- `Act33SignRedpackListView _listView`

- `GameObject _infoPanel`

- `GameObject _redpackAvailablePanel`

- `Text _nextRedpackTips`

- `ExtraSignPluginOptions m_optionStruct`

- `Act33SignRedpackViewModel m_viewModel`


## Methods

- `Void InitPlugin(ExtraSignPluginOptions)`

- `Void RefreshPlugin()`

- `Void _RenderInfoPanel(Act33SignRedpackViewModel)`

- `String _GenRedpackTips(Act33SignRedpackViewModel)`

- `Boolean _JudgeShouldReplaceNew(Int32, Act33SignRedpackItemViewModel)`

- `Void _RenderListView(Act33SignRedpackViewModel)`

- `Void _RenderDetailView(Act33SignRedpackViewModel)`

- `Void OnRedpackListClick()`

- `Void OnRedpackDetailClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act33Sign
public class Act33SignPlugin : MonoBehaviour, ITemplateActivityExtraSignPlugin, IHotfixable
{
	private Act33SignRedpackDetailView _detailView; // 0x18
	private Act33SignRedpackListView _listView; // 0x20
	private GameObject _infoPanel; // 0x28
	private GameObject _redpackAvailablePanel; // 0x30
	private Text _nextRedpackTips; // 0x38
	private Text[] _mainRewardCountDowns; // 0x40
	private ExtraSignPluginOptions m_optionStruct; // 0x48
	private Act33SignRedpackViewModel m_viewModel; // 0x50
	private static DelegateBridge __Hotfix0_InitPlugin; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlugin; // 0x8
	private static DelegateBridge __Hotfix0__RenderInfoPanel; // 0x10
	private static DelegateBridge __Hotfix0__GenRedpackTips; // 0x18
	private static DelegateBridge __Hotfix0__JudgeShouldReplaceNew; // 0x20
	private static DelegateBridge __Hotfix0__RenderListView; // 0x28
	private static DelegateBridge __Hotfix0__RenderDetailView; // 0x30
	private static DelegateBridge __Hotfix0_OnRedpackListClick; // 0x38
	private static DelegateBridge __Hotfix0_OnRedpackDetailClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3253dbc VA: 0x759586bdbc
	public Void InitPlugin(ExtraSignPluginOptions options) { }
	// RVA: 0x3253e40 VA: 0x759586be40
	public Void RefreshPlugin() { }
	// RVA: 0x3254620 VA: 0x759586c620
	private Void _RenderInfoPanel(Act33SignRedpackViewModel viewModel) { }
	// RVA: 0x3254a0c VA: 0x759586ca0c
	private String _GenRedpackTips(Act33SignRedpackViewModel viewModel) { }
	// RVA: 0x3254bec VA: 0x759586cbec
	private Boolean _JudgeShouldReplaceNew(Int32 closestDay, Act33SignRedpackItemViewModel newItem) { }
	// RVA: 0x3254ca0 VA: 0x759586cca0
	private Void _RenderListView(Act33SignRedpackViewModel viewModel) { }
	// RVA: 0x3254894 VA: 0x759586c894
	private Void _RenderDetailView(Act33SignRedpackViewModel viewModel) { }
	// RVA: 0x32551c8 VA: 0x759586d1c8
	public Void OnRedpackListClick() { }
	// RVA: 0x3255234 VA: 0x759586d234
	public Void OnRedpackDetailClick() { }
	// RVA: 0x32552a0 VA: 0x759586d2a0
	public Void .ctor() { }
}
```