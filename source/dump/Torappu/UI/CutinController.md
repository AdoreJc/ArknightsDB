# CutinController

**Namespace:** `Torappu.UI`


## Fields

- `GameObjectPoolComponent _channelPool`

- `ILoadAsset m_assetLoader`

- `Options m_initOptions`

- `CutinParam m_cutin`

- `Boolean m_IsInited`


## Properties

- `Boolean isRunning`


## Methods

- `Void InitCutin(Options)`

- `Boolean get_isRunning()`

- `Void RunCutin(CutinParam, Action)`

- `Void _ProcessChannelClean(CutinParam, Action)`

- `Void _ProcessChannel(CutinParam, Action)`

- `Void StopCutin(String, Boolean)`

- `Void EndCutin(String, Boolean)`

- `Void Reset()`

- `Void <EndCutin>b__14_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CutinController : MonoBehaviour, IHotfixable
{
	private GameObjectPoolComponent _channelPool; // 0x18
	private ILoadAsset m_assetLoader; // 0x20
	private Options m_initOptions; // 0x28
	private Dictionary`2 _cutinChannels; // 0x38
	private CutinParam m_cutin; // 0x40
	private Boolean m_IsInited; // 0x48
	private static DelegateBridge __Hotfix0_InitCutin; // 0x0
	private static DelegateBridge __Hotfix0_get_isRunning; // 0x8
	private static DelegateBridge __Hotfix0_RunCutin; // 0x10
	private static DelegateBridge __Hotfix0__ProcessChannelClean; // 0x18
	private static DelegateBridge __Hotfix0__ProcessChannel; // 0x20
	private static DelegateBridge __Hotfix0_StopCutin; // 0x28
	private static DelegateBridge __Hotfix0_EndCutin; // 0x30
	private static DelegateBridge __Hotfix0_Reset; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean isRunning { get; }

	// RVA: 0x216b9e4 VA: 0x75947839e4
	public Void InitCutin(Options initOptions) { }
	// RVA: 0x216ba8c VA: 0x7594783a8c
	public Boolean get_isRunning() { }
	// RVA: 0x216bafc VA: 0x7594783afc
	public Void RunCutin(CutinParam param, Action onCutinEnd) { }
	// RVA: 0x216bca8 VA: 0x7594783ca8
	private Void _ProcessChannelClean(CutinParam param, Action onCutinEnd) { }
	// RVA: 0x216c098 VA: 0x7594784098
	private Void _ProcessChannel(CutinParam param, Action onCutinEnd) { }
	// RVA: 0x216c4a4 VA: 0x75947844a4
	public Void StopCutin(String errorMsg, Boolean isInterrupt) { }
	// RVA: 0x216c54c VA: 0x759478454c
	public Void EndCutin(String errorMsg, Boolean isInterrupt) { }
	// RVA: 0x216c688 VA: 0x7594784688
	public Void Reset() { }
	// RVA: 0x216c88c VA: 0x759478488c
	public Void .ctor() { }
	// RVA: 0x216c950 VA: 0x7594784950
	private Void <EndCutin>b__14_0() { }
}
```