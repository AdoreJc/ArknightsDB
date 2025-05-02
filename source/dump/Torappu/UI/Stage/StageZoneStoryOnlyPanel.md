# StageZoneStoryOnlyPanel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIBlurFloatPanel _floatPanel`

- `Text _stageCodeText`

- `Text _stageTitleText`

- `Text _stageDescText`

- `Action m_startHandler`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Show(String, String, String, Action)`

- `Void Hide()`

- `Void OnStartButtonPressed()`

- `Void OnBackgroundPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneStoryOnlyPanel : MonoBehaviour, IHotfixable
{
	private UIBlurFloatPanel _floatPanel; // 0x18
	private Text _stageCodeText; // 0x20
	private Text _stageTitleText; // 0x28
	private Text _stageDescText; // 0x30
	private Action m_startHandler; // 0x38
	private Boolean m_isInited; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0_Hide; // 0x10
	private static DelegateBridge __Hotfix0_OnStartButtonPressed; // 0x18
	private static DelegateBridge __Hotfix0_OnBackgroundPressed; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2f75458 VA: 0x759558d458
	private Void _InitIfNot() { }
	// RVA: 0x2f75568 VA: 0x759558d568
	public Void Show(String stageCode, String stageTitle, String stageDesc, Action startHandler) { }
	// RVA: 0x2f75754 VA: 0x759558d754
	public Void Hide() { }
	// RVA: 0x2f757e8 VA: 0x759558d7e8
	public Void OnStartButtonPressed() { }
	// RVA: 0x2f75878 VA: 0x759558d878
	public Void OnBackgroundPressed() { }
	// RVA: 0x2f758f8 VA: 0x759558d8f8
	public Void .ctor() { }
}
```