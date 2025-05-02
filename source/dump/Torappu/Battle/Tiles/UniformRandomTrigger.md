# UniformRandomTrigger

**Namespace:** `Torappu.Battle.Tiles`


## Fields

- `Single _preDelay`

- `String _preDelayEffect`

- `Single _defaultInterval`

- `Single m_minCd`

- `Single m_maxCd`


## Methods

- `IEnumerator _DoTrigProcess()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Tiles
public class UniformRandomTrigger : Behaviour
{
	private const String BLACKBOARD_KEY_CD_MIN; // 0x0
	private const String BLACKBOARD_KEY_CD_MAX; // 0x0
	private Single _preDelay; // 0x20
	private String _preDelayEffect; // 0x28
	private Single _defaultInterval; // 0x30
	private Single m_minCd; // 0x34
	private Single m_maxCd; // 0x38


	// RVA: 0x1dae71c VA: 0x75943c671c
	public override Void Init(Tile tile) { }
	// RVA: 0x1dae80c VA: 0x75943c680c
	public override Void OnGameStart() { }
	// RVA: 0x1dae8f8 VA: 0x75943c68f8
	public override Void OnGameOver(GameResult result) { }
	// RVA: 0x1dae970 VA: 0x75943c6970
	public override Void PreloadAssets() { }
	// RVA: 0x1dae884 VA: 0x75943c6884
	private IEnumerator _DoTrigProcess() { }
	// RVA: 0x1daea34 VA: 0x75943c6a34
	public Void .ctor() { }
}
```