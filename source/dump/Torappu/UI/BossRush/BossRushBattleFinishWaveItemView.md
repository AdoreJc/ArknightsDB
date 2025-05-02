# BossRushBattleFinishWaveItemView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `Text _textWave`

- `UIAtlasImage _imgCaption`

- `GameObject _finalWaveBg`

- `GameObject _normalWaveBg`

- `Color _colorFinal`

- `Color _colorNormnal`

- `Single _alphaNotLast`

- `GameObject _bossIconGo`

- `UIAtlasImage _iconBoss`

- `SimpleLayoutContent _bossIconList`

- `Color _colorNormalBossIcon`

- `Color _colorFinalBossIcon`

- `Single _alphaBossIcon`


## Methods

- `Void Render(Int32, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushBattleFinishWaveItemView : MonoBehaviour, IHotfixable
{
	private Text _textWave; // 0x18
	private UIAtlasImage _imgCaption; // 0x20
	private GameObject _finalWaveBg; // 0x28
	private GameObject _normalWaveBg; // 0x30
	private Color _colorFinal; // 0x38
	private Color _colorNormnal; // 0x48
	private Single _alphaNotLast; // 0x58
	private GameObject _bossIconGo; // 0x60
	private UIAtlasImage _iconBoss; // 0x68
	private SimpleLayoutContent _bossIconList; // 0x70
	private Color _colorNormalBossIcon; // 0x78
	private Color _colorFinalBossIcon; // 0x88
	private Single _alphaBossIcon; // 0x98
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2e568b8 VA: 0x759546e8b8
	public Void Render(Int32 currentWave, Boolean isFinalWave, Boolean isLastWave) { }
	// RVA: 0x2e576c8 VA: 0x759546f6c8
	public Void .ctor() { }
}
```