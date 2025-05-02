# EnemyDuelFinishMultiBattleServiceConfig

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String m_actId`

- `String m_sceneId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelFinishMultiBattleServiceConfig : FinishBattleServiceConfig`2
{
	private String m_actId; // 0x18
	private String m_sceneId; // 0x20


	// RVA: 0x2943bd8 VA: 0x7594f5bbd8
	public Void .ctor(String actId, String sceneId) { }
	// RVA: 0x2943c70 VA: 0x7594f5bc70
	public override Void OnParseRequest(EnemyDuelMultiBattleFinishRequest request) { }
}
```