# Story

**Namespace:** `Torappu.AVG`


## Fields

- `String id`

- `String title`

- `String briefId`

- `Boolean isTutorial`

- `Boolean isSkippable`

- `Boolean isAutoable`

- `Boolean isVideoOnly`

- `Boolean denyAutoSwitchScene`

- `Boolean dontClearGameObjectPoolOnStart`

- `FitMode fitMode`

- `CharacterSortType characterSortType`

- `StoryParam param`

- `StoryOutPut m_outPut`


## Properties

- `StoryOutPut Output`

- `String OverrideId`


## Methods

- `StoryOutPut get_Output()`

- `Void set_Output(StoryOutPut)`

- `String TryGetStrParam(String)`

- `String get_OverrideId()`

- `Void set_OverrideId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class Story
{
	public const String STORY_PARAM_GOTO_CHARINFOID; // 0x0
	public String id; // 0x10
	public String title; // 0x18
	public String briefId; // 0x20
	public Boolean isTutorial; // 0x28
	public Boolean isSkippable; // 0x29
	public Boolean isAutoable; // 0x2a
	public Boolean isVideoOnly; // 0x2b
	public Boolean denyAutoSwitchScene; // 0x2c
	public Boolean dontClearGameObjectPoolOnStart; // 0x2d
	public FitMode fitMode; // 0x30
	public CharacterSortType characterSortType; // 0x34
	public StoryParam param; // 0x38
	public List`1 commands; // 0x50
	private StoryOutPut m_outPut; // 0x58

	public StoryOutPut Output { get; set; }
	public String OverrideId { get; set; }

	// RVA: 0x3e9c5cc VA: 0x75964b45cc
	public StoryOutPut get_Output() { }
	// RVA: 0x3e9c5d4 VA: 0x75964b45d4
	public Void set_Output(StoryOutPut value) { }
	// RVA: 0x3e9c5e0 VA: 0x75964b45e0
	public String TryGetStrParam(String paramName) { }
	// RVA: 0x3e9c6fc VA: 0x75964b46fc
	public String get_OverrideId() { }
	// RVA: 0x3e9c704 VA: 0x75964b4704
	public Void set_OverrideId(String value) { }
	// RVA: 0x3e9c70c VA: 0x75964b470c
	public Void .ctor() { }
}
```