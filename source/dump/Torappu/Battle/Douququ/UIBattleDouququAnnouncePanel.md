# UIBattleDouququAnnouncePanel

**Namespace:** `Torappu.Battle.Douququ`


## Fields

- `GameObject _objStartPart`

- `GameObject _objWavePart`

- `Text _curWave`

- `Text _totleWave`

- `AnimationWrapper _startAnim`

- `DouququUIAnnounceState m_state`


## Methods

- `Void Init(DouququUIAnnounceState)`

- `Void Show(Boolean, DouququGameMode)`

- `Void _OnAnnounceEnd()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Douququ
public class UIBattleDouququAnnouncePanel : MonoBehaviour, IHotfixable
{
	private GameObject _objStartPart; // 0x18
	private GameObject _objWavePart; // 0x20
	private Text _curWave; // 0x28
	private Text _totleWave; // 0x30
	private AnimationWrapper _startAnim; // 0x38
	private DouququUIAnnounceState m_state; // 0x40
	private const String DOUQUQU_START_ANIM; // 0x0
	private const String DOUQUQU_WAVE_START_ANIM; // 0x0
	private const Int32 LARGE_WAVE_SIZE; // 0x0
	private const Int32 SMALL_WAVE_SIZE; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0__OnAnnounceEnd; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1dcfd50 VA: 0x75943e7d50
	public Void Init(DouququUIAnnounceState announceState) { }
	// RVA: 0x1dcfdd4 VA: 0x75943e7dd4
	public Void Show(Boolean isFirstShow, DouququGameMode manager) { }
	// RVA: 0x1dd00f4 VA: 0x75943e80f4
	private Void _OnAnnounceEnd() { }
	// RVA: 0x1dd01f0 VA: 0x75943e81f0
	public Void .ctor() { }
}
```