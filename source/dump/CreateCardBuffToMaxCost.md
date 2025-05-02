# CreateCardBuffToMaxCost

**Namespace:** ` `


## Fields

- `String _excludeCardBuffKey`

- `String _cardBuffEffectPlugin`

- `State _manuallyChangeCardState`

- `String _playAudio`


## Properties

- `Boolean isTimeLimited`


## Methods

- `Boolean get_isTimeLimited()`

- `Boolean _ExcludeCard(Card)`

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Boolean <>xLuaBaseProxy_Execute(Blackboard, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateCardBuffToMaxCost : BaseCreateCardBuff
{
	private String _excludeCardBuffKey; // 0x20
	private String _cardBuffEffectPlugin; // 0x28
	private State _manuallyChangeCardState; // 0x30
	private String _playAudio; // 0x38
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_isTimeLimited; // 0x8
	private static DelegateBridge __Hotfix0__ExcludeCard; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	protected Boolean isTimeLimited { get; }

	// RVA: 0x1f70fc0 VA: 0x7594588fc0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f71028 VA: 0x7594589028
	protected Boolean get_isTimeLimited() { }
	// RVA: 0x1f710a0 VA: 0x75945890a0
	private Boolean _ExcludeCard(Card card) { }
	// RVA: 0x1f71178 VA: 0x7594589178
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f714f8 VA: 0x75945894f8
	public Void .ctor() { }
	// RVA: 0x1f71568 VA: 0x7594589568
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f71570 VA: 0x7594589570
	private Boolean <>xLuaBaseProxy_Execute(Blackboard P0, SourceType P1, ref Snapshot P2) { }
}
```