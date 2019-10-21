### Comments

There aren't any comments, so it can be confusing if you don't know the project

```{JavaScript}
const HomeScreen = (props) => {
  return (
  <View>
    <Text style={styles.text}>Care Map</Text>
    <TouchableOpacity onPress={() => props.navigation.navigate("Components")}>
      <Text>Go To Components</Text>
    </TouchableOpacity>
  <TouchableOpacity onPress={() => props.navigation.navigate("List")}>
      <Text>Go to List</Text>
    </TouchableOpacity>
    <TouchableOpacity onPress={() => props.navigation.navigate("Rate Us")}>
      <Text>Go to Rating</Text>
    </TouchableOpacity>
  </View>
  );
};
```
