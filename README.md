package application;

import javafx.application.Application;
import javafx.scene.Scene;
import javafx.scene.control.Button;
import javafx.scene.layout.StackPane;
import javafx.stage.Stage;


public class Main extends Application {
    
    @Override
    public void start(Stage primaryStage) {
StackPane pane = new StackPane();
pane.getChildren().add(new Button("OK"));
Scene scene = new Scene(pane , 200 , 350);
primaryStage.setTitle("Button in a pane");
primaryStage.setScene(scene);
primaryStage.show();
    }
public static void main(String[] args) {
        launch(args);
    }
    
}
