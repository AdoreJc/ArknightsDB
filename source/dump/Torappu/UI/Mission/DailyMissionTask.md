# DailyMissionTask

**Namespace:** `Torappu.UI.Mission`


## Fields

- `Image _backgroundImage`

- `GameObject _backgroundGlow`

- `GameObject _acceptButtonGlow`

- `Text _description`

- `Image _requireLabelBackground`

- `Text _requireLabelText`

- `Text _pointNumberLabel`

- `Image _pointIconImage`

- `RectTransform _crossRectTransform`

- `GameObject _finished`

- `GameObject _unfinished`

- `GameObject _accepted`

- `MissionProgressBar _missionState`

- `Text _progressTarget`

- `Text _progressValue`

- `CanvasGroup _alphaHandler`

- `ViewStyle normalStyle`

- `ViewStyle completeStyle`

- `MissionViewModel m_dataCache`


## Methods

- `Void _ApplyViewStyle(ViewStyle)`

- `Void ApplyReward()`

- `Void OnOpenDetailClick()`

- `Void AsyncShow()`

- `Void AsyncSetData(MissionViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class DailyMissionTask : MonoBehaviour, IHotfixable, IAsyncDataView`1, IAsyncShowEffect
{
	private Image _backgroundImage; // 0x18
	private GameObject _backgroundGlow; // 0x20
	private GameObject _acceptButtonGlow; // 0x28
	private Text _description; // 0x30
	private Image _requireLabelBackground; // 0x38
	private Text _requireLabelText; // 0x40
	private Text _pointNumberLabel; // 0x48
	private Image _pointIconImage; // 0x50
	private RectTransform _crossRectTransform; // 0x58
	private GameObject _finished; // 0x60
	private GameObject _unfinished; // 0x68
	private GameObject _accepted; // 0x70
	private MissionProgressBar _missionState; // 0x78
	private Text _progressTarget; // 0x80
	private Text _progressValue; // 0x88
	private CanvasGroup _alphaHandler; // 0x90
	private ViewStyle normalStyle; // 0x98
	private ViewStyle completeStyle; // 0xa0
	private MissionViewModel m_dataCache; // 0xa8
	private static DelegateBridge __Hotfix0__ApplyViewStyle; // 0x0
	private static DelegateBridge __Hotfix0_ApplyReward; // 0x8
	private static DelegateBridge __Hotfix0_OnOpenDetailClick; // 0x10
	private static DelegateBridge __Hotfix0_AsyncShow; // 0x18
	private static DelegateBridge __Hotfix0_AsyncSetData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x273bef4 VA: 0x7594d53ef4
	private Void _ApplyViewStyle(ViewStyle style) { }
	// RVA: 0x273c1d4 VA: 0x7594d541d4
	public Void ApplyReward() { }
	// RVA: 0x273c254 VA: 0x7594d54254
	public Void OnOpenDetailClick() { }
	// RVA: 0x273c2cc VA: 0x7594d542cc
	public Void AsyncShow() { }
	// RVA: 0x273c3a4 VA: 0x7594d543a4
	public Void AsyncSetData(MissionViewModel data) { }
	// RVA: 0x273c664 VA: 0x7594d54664
	public Void .ctor() { }
}
```