# AutoChessGameModeVoicePlugin

**Namespace:** `Torappu.Battle.UI`


## Fields

- `AutoChessGameMode m_autoChessGameMode`


## Properties

- `AutoChessGameMode gameMode`


## Methods

- `AutoChessGameMode get_gameMode()`

- `Void _OnRoundStarted(Object)`

- `Void _OnPlaceAtBattleFieldInShop(Object)`

- `Void _OnCharacterHighlighted(Object)`

- `Void <>xLuaBaseProxy_Init(VoicePlayer)`

- `Boolean <>xLuaBaseProxy_HookPlayVoice(ref, ref, ref, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class AutoChessGameModeVoicePlugin : DefaultGamePlugin
{
	private AutoChessGameMode m_autoChessGameMode; // 0x18
	private List`1 m_battleInstCache; // 0x20
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_HookPlayVoice; // 0x10
	private static DelegateBridge __Hotfix0__OnRoundStarted; // 0x18
	private static DelegateBridge __Hotfix0__OnPlaceAtBattleFieldInShop; // 0x20
	private static DelegateBridge __Hotfix0__OnCharacterHighlighted; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private AutoChessGameMode gameMode { get; }

	// RVA: 0x208baa0 VA: 0x75946a3aa0
	private AutoChessGameMode get_gameMode() { }
	// RVA: 0x208bbcc VA: 0x75946a3bcc
	public override Void Init(VoicePlayer voicePlayer) { }
	// RVA: 0x208bdb0 VA: 0x75946a3db0
	public override Boolean HookPlayVoice(ref BattleVoiceType voiceType, ref VoiceQuery vq, ref MapLayer mapLayer, out PlayResult result) { }
	// RVA: 0x208bec4 VA: 0x75946a3ec4
	private Void _OnRoundStarted(Object arg) { }
	// RVA: 0x208c0a8 VA: 0x75946a40a8
	private Void _OnPlaceAtBattleFieldInShop(Object arg) { }
	// RVA: 0x208c258 VA: 0x75946a4258
	private Void _OnCharacterHighlighted(Object arg) { }
	// RVA: 0x208c3d0 VA: 0x75946a43d0
	public Void .ctor() { }
	// RVA: 0x208c490 VA: 0x75946a4490
	private Void <>xLuaBaseProxy_Init(VoicePlayer P0) { }
	// RVA: 0x208c494 VA: 0x75946a4494
	private Boolean <>xLuaBaseProxy_HookPlayVoice(ref BattleVoiceType P0, ref VoiceQuery P1, ref MapLayer P2, out PlayResult P3) { }
}
```