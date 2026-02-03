public class Equipment {
   
    public Resources resources;
    public int computerFixed;
   
    public Equipment() {
        resources = new Resources();
        computerFixed = 0;
    }
   
    public Equipment(int initialFixed) {
        resources = new Resources();
        computerFixed = initialFixed;
    }
   
    public Equipment(Resources res, int initialFixed) {
        resources = res;
        computerFixed = initialFixed;
    }
   
    public double totalComputers() {
        return 50.0; 
    }
   
    public boolean computerFixed() {
        return computerFixed > 0;
    }
}


//Section below copy paste sa main.
//Equipment eq = new Equipment(22);

// Or with both values
//Resources myResources = new Resources();
//Equipment eq2 = new Equipment(myResources, 22);

//System.out.println(eq.computerFixed);
//System.out.println(eq.computerFixed());
