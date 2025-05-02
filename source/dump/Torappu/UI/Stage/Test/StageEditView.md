# StageEditView

**Namespace:** `Torappu.UI.Stage.Test`


## Fields

- `StageDB _stageDB`

- `ZoneDB _zoneDB`

- `StageMainZoneMap _mainZoneMapPrefab`

- `String _zoneId`


## Properties

- `Single positionValue`

- `Single backgroundImageRefValue`


## Methods

- `UIPage GetPage()`

- `Single get_positionValue()`

- `Single get_backgroundImageRefValue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.Test
public class StageEditView : MonoBehaviour, IStageMainZoneMapController
{
	private const String ALERT_EDIT_MODE_ONLY; // 0x0
	private StageDB _stageDB; // 0x18
	private ZoneDB _zoneDB; // 0x20
	private StageMainZoneMap _mainZoneMapPrefab; // 0x28
	private String _zoneId; // 0x30

	public Single positionValue { get; }
	public Single backgroundImageRefValue { get; }

	// RVA: 0x2fe04dc VA: 0x75955f84dc
	public UIPage GetPage() { }
	// RVA: 0x2fe04e4 VA: 0x75955f84e4
	public Single get_positionValue() { }
	// RVA: 0x2fe04ec VA: 0x75955f84ec
	public Single get_backgroundImageRefValue() { }
	// RVA: 0x2fe04f4 VA: 0x75955f84f4
	public Void .ctor() { }
}
```