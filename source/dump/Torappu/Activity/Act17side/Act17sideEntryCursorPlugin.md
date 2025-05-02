# Act17sideEntryCursorPlugin

**Namespace:** `Torappu.Activity.Act17side`


## Fields

- `RectTransform _cursor`

- `Tween m_tween`

- `Boolean m_hasPlayedEntryAnim`

- `String m_activityId`

- `Act17sideActivityZoneGroupViewModel m_cachedViewModel`


## Methods

- `Void _InitIfNot(String)`

- `Tween _GenerateTweenOfEntry(Boolean)`

- `Tween _GenerateTweenOfZoneSelected()`

- `Void _OpenRPPage(String)`

- `Void OnLoaded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act17side
public class Act17sideEntryCursorPlugin : TemplateActivityCommonPlugin
{
	private const String DEFAULT_POS_KEY; // 0x0
	public const String LAST_OPEN_ZONE_KEY; // 0x0
	private List`1 _cursorItems; // 0x28
	private RectTransform _cursor; // 0x30
	private Tween m_tween; // 0x38
	private Boolean m_hasPlayedEntryAnim; // 0x40
	private Dictionary`2 m_cursorMap; // 0x48
	private String m_activityId; // 0x50
	private Act17sideActivityZoneGroupViewModel m_cachedViewModel; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__GenerateTweenOfEntry; // 0x8
	private static DelegateBridge __Hotfix0__GenerateTweenOfZoneSelected; // 0x10
	private static DelegateBridge __Hotfix0__OpenRPPage; // 0x18
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x20
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3419ea8 VA: 0x7595a31ea8
	private Void _InitIfNot(String activityId) { }
	// RVA: 0x341a0e4 VA: 0x7595a320e4
	private Tween _GenerateTweenOfEntry(Boolean backFromBatlle) { }
	// RVA: 0x341a414 VA: 0x7595a32414
	private Tween _GenerateTweenOfZoneSelected() { }
	// RVA: 0x341a81c VA: 0x7595a3281c
	private Void _OpenRPPage(String zoneId) { }
	// RVA: 0x341a970 VA: 0x7595a32970
	public Void OnLoaded() { }
	// RVA: 0x341aaa4 VA: 0x7595a32aa4
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x341ad48 VA: 0x7595a32d48
	public Void .ctor() { }
}
```