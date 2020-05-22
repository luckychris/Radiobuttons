# Radiobuttons
SwiftUI Radiobuttons - easy to use

This is an easy to use SwiftUI Radiobuttons implementation. Have fun using it!

You can implement it just by a few lines of code like this:

struct ContentView: View {
    var body: some View {
        HStack {
            Text("Example")
                .font(Font.headline)
                .padding()
            RadioButtonGroup(items: ["Rome", "London", "Paris", "Berlin", "New York"], selectedId: "London") { selected in
                print("Selected is: \(selected)")
            }
        }.padding()
    }
}



![Example 2](/Example2.png)
![Example 1](/Example1.png)
