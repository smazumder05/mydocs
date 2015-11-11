```java

package com.sm.utils.ds;

import java.util.AbstractList;
import java.util.Collection;

/**
 *
 * @author smazumder6
 */
public class SmVector<E> extends AbstractList<E> implements Cloneable {
    

    /**
     * Create an empty SmVector with an initial capacity of initialCapacity and
     * increments its size by capacityIncrement
     * 
     * @param initialCapacvity
     * @param capacityIncrement 
     */
    public SmVector(int initialCapacvity, int capacityIncrement) {
        
    }
    
    /**
     * Creates a SmVector with an initial capacity of initialCapacity.
     * <pre> InitialCapacity >= 0
     * <post> an empty SmVector is created with the specified initial capacity.
     * 
     * @param initialCapacity 
     * @throws IllegalArgumentException of the initialCapacity is negative.
     * 
     */
    public SmVector(int initialCapacity) {
        
    }
    
    /**
     * constructs an empty SmVector with a default capacity of 10.
     * 
     */
    public SmVector() {
        
    }
    
    /**
     * Constructs a SmVector containing the elements of the specified
     * collection. In the order they are returned by the collection's 
     * iterator.
     * 
     * 
     * @param c 
     * @throws IllegalArgumentException if the Collection is null.
     * 
     */
    public SmVector(Collection<? extends E> c) {
        
    }
    
    /**
     * Adds the element E at the end of this vector thus increasing 
     * its size by 1.  The capacity of the vector is increased if the size becomes
     * greater than its capacity.
     * 
     * <pre> SmVector has been initialized.
     * <post> SmVector adds the element at the end.
     * 
     * @param obj 
     */
    public void addElement(E obj) {
        
    }
    
    /**
     * Removes the first (lowest index) occurrence of the element from this 
     * vector. Each component of the vector is then shifted towards the left
     * such that its index becomes less by 1.
     * 
     * <pre> obj is not null.
     * {@link #remove(Object)} method (which is part of the
     * {@link List} interface).
     * 
     * @param obj the component to be removed
     * @return {@code true} if the argument was a component of this vector,
     *         {@code false} otherwise.
     * 
     */
    public boolean removeElement(E obj) {
        return false;
    }
    
    /**
     * returns the current size of this vector.
     * <pre> Smvector has been initialized.
     * <post> returns the current size of this vector.
     * @return 
     */
    public int size() {
        return 0;
    }
}
```
