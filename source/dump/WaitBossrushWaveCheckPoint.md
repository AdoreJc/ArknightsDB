# WaitBossrushWaveCheckPoint

**Namespace:** ` `


## Fields

- `Int32 m_bossrushWave`

- `BossRushGameMode m_bossRushGameMode`


## Properties

- `Boolean isReached`


## Methods

- `Boolean get_isReached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class WaitBossrushWaveCheckPoint : Checkpoint
{
	private Int32 m_bossrushWave; // 0x20
	private BossRushGameMode m_bossRushGameMode; // 0x28

	public Boolean isReached { get; }

	// RVA: 0x407e1a8 VA: 0x75966961a8
	public Boolean get_isReached() { }
	// RVA: 0x407caa4 VA: 0x7596694aa4
	public Void .ctor(CheckpointData data, BasicCursor cursor) { }
	// RVA: 0x407e200 VA: 0x7596696200
	public override Boolean CheckReached(GridPosition grid) { }
	// RVA: 0x407e204 VA: 0x7596696204
	public override Boolean CheckReached(Vector2 pos) { }
	// RVA: 0x407e208 VA: 0x7596696208
	public override Vector2 GetNextDirection(Vector2 pos) { }
	// RVA: 0x407e248 VA: 0x7596696248
	public override GridPosition GetNextGrid(GridPosition grid) { }
	// RVA: 0x407e250 VA: 0x7596696250
	public override Void OnBegin() { }
}
```