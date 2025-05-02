# GameCityWaveStartPanel

**Namespace:** `Torappu.Activity.GameCity.Battle.UI`


## Fields

- `Text _maxWaveText`

- `Text _maxWaveTextShadow`

- `Text _curWaveText`

- `Text _curWaveTextShadow`

- `Text _curWaveShowText`

- `Text _curWaveShowTextShadow`

- `UIAtlasImage _atlasImage`

- `UIAtlasObject _atlasObj`

- `UIAtlasImage _atlasImageShadow`

- `UIPerform uiPerform`


## Methods

- `Void OnUpdateWaveInfo(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.GameCity.Battle.UI
public class GameCityWaveStartPanel : MonoBehaviour, IHotfixable
{
	private Text _maxWaveText; // 0x18
	private Text _maxWaveTextShadow; // 0x20
	private Text _curWaveText; // 0x28
	private Text _curWaveTextShadow; // 0x30
	private Text _curWaveShowText; // 0x38
	private Text _curWaveShowTextShadow; // 0x40
	private UIAtlasImage _atlasImage; // 0x48
	private UIAtlasObject _atlasObj; // 0x50
	private UIAtlasImage _atlasImageShadow; // 0x58
	private List`1 _waveTextShow; // 0x60
	private List`1 _waveIconShow; // 0x68
	public UIPerform uiPerform; // 0x70
	private static DelegateBridge __Hotfix0_OnUpdateWaveInfo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x33e9b9c VA: 0x7595a01b9c
	public Void OnUpdateWaveInfo(Int32 currWaveCnt, Int32 maxWaveCnt) { }
	// RVA: 0x33ebfe0 VA: 0x7595a03fe0
	public Void .ctor() { }
}
```