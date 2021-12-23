Swift UI code

(Navigation List)



import SwiftUI

struct ContentView: view {

​	var body: some View {

​		NavigationView() {

​			List( ) {

​				NavigationLink(destination: Text("Hello, world!"))

​				{

​				Text("Touch Me")

​				}

​			}

​			.navigationBarTitle("Tutorials")

​		}

​		Text("Hello, world!").padding( )

​	}

}

Struct ContentView_Preview: PreviewProvider {

​	static var preview: some View {

​		ContentView()		

​	}

}