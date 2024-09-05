# Budget-App-UIKit
Set up core data stack
In Scene Delegate
1] import coreData
2] lazy var var_name : NSPersistentContainer = {
    let container =  NSPersistentContainer (name = "name of ccore data file")
    //load persistant container 
        container.loadpersistantStores { description, error in 
        if let error = error { 
        fetalerror("error")
        }
        }
        return container
        }()
pass persistantContainer to the BudgetcotegorytableViewcontroller.
# instead of BudgetcotegorytableViewcontroller use navigation container as a root view container.
***********************************************************************
