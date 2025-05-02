# DailyMissionRewardTask

**Namespace:** `Torappu.UI.Mission`


## Fields

- `MissionRewardPreviewItem _item1`

- `MissionRewardPreviewItem _item2`

- `GameObject _finished`

- `CanvasGroup _canvasGroup`

- `Single _completeAlpha`

- `Text _serialNumberLabel`

- `String m_dataCacheId`

- `MissionType m_dataCacheIdType`

- `Int32 m_serialNumber`

- `Int32 m_rewardState`

- `Boolean m_isFinish`


## Properties

- `Int32 serialNumber`

- `Int32 rewardState`


## Methods

- `Void _SetFinished(Boolean)`

- `Int32 get_serialNumber()`

- `Int32 get_rewardState()`

- `Void AsyncShow()`

- `Void AsyncSetData(Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class DailyMissionRewardTask : MonoBehaviour, IHotfixable, IAsyncDataView`1, IAsyncShowEffect
{
	private MissionRewardPreviewItem _item1; // 0x18
	private MissionRewardPreviewItem _item2; // 0x20
	private DailyMissionRewardPoint[] _points; // 0x28
	private GameObject _finished; // 0x30
	private CanvasGroup _canvasGroup; // 0x38
	private Single _completeAlpha; // 0x40
	private Text _serialNumberLabel; // 0x48
	private String m_dataCacheId; // 0x50
	private MissionType m_dataCacheIdType; // 0x58
	private Int32 m_serialNumber; // 0x5c
	private Int32 m_rewardState; // 0x60
	private Boolean m_isFinish; // 0x64
	private static DelegateBridge __Hotfix0__SetFinished; // 0x0
	private static DelegateBridge __Hotfix0_get_serialNumber; // 0x8
	private static DelegateBridge __Hotfix0_get_rewardState; // 0x10
	private static DelegateBridge __Hotfix0_AsyncShow; // 0x18
	private static DelegateBridge __Hotfix0_AsyncSetData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Int32 serialNumber { get; }
	public Int32 rewardState { get; }

	// RVA: 0x273a160 VA: 0x7594d52160
	private Void _SetFinished(Boolean finish) { }
	// RVA: 0x273a27c VA: 0x7594d5227c
	public Int32 get_serialNumber() { }
	// RVA: 0x273a2e4 VA: 0x7594d522e4
	public Int32 get_rewardState() { }
	// RVA: 0x273a34c VA: 0x7594d5234c
	public Void AsyncShow() { }
	// RVA: 0x273a3fc VA: 0x7594d523fc
	public Void AsyncSetData(Data dataWrapper) { }
	// RVA: 0x273a6dc VA: 0x7594d526dc
	public Void .ctor() { }
}
```