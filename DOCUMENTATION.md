# Godot_ButtonRemapper API Reference
Generated: 2026-03-09

This addon is used for remapping buttons. It can be used for allowing the player to edit the input settings

## Class: smoothButtonRemapperButton
**Inherits:** [SmoothButton](https://github.com/ChillCube/Godot_SpriteBasedSmoothMenuButton2D.git/blob/main/DOCUMENTATION.md)


### ⚙️ Inspector Variables
| Property | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| **action_to_rebind** | `String` | `"ui_left"` |  |

### 🔔 Signals
| Signal | Arguments | Description |
| :--- | :--- | :--- |
| **awaiting_input** | - |  |
| **button_remapped** | action_name | - |

### 🛠️ Methods
| Method | Arguments | Returns | Description |
| :--- | :--- | :--- | :--- |
| **set_text_color()** | color: Color | `void` | - |
| **get_current_input_string()** | - | `String` | - |

---

## Class: ButtonRemapper
**Inherits:** [Node](https://docs.godotengine.org/en/stable/classes/class_node.html)


### ⚙️ Inspector Variables
| Property | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| **action_to_rebind** | `String` | `"ui_up"` |  |

### 🔔 Signals
| Signal | Arguments | Description |
| :--- | :--- | :--- |
| **awaiting_input** | - |  |
| **_key_chosen** | index | - |
| **button_remapped** | action_name | - |

### 🛠️ Methods
| Method | Arguments | Returns | Description |
| :--- | :--- | :--- | :--- |
| **remap_keybind()** | action : String = action_to_rebind | `InputEvent` |  |

---

## Class: buttonRemapperButton
**Inherits:** [Button](https://docs.godotengine.org/en/stable/classes/class_button.html)

This is a button that players can use to remape buttons. It will be useful for keybinds settings in the game. 

### ⚙️ Inspector Variables
| Property | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| **action_to_rebind** | `String` | `"ui_left"` | This is a button that players can use to remape buttons. It will be useful for keybinds settings in the game. |

### 🔔 Signals
| Signal | Arguments | Description |
| :--- | :--- | :--- |
| **awaiting_input** | - | This is a button that players can use to remape buttons. It will be useful for keybinds settings in the game. |
| **button_remapped** | action_name | - |

---

