Annotations

@Entity
@Table(name="EMPLOYEE")
@Id @GeneratedValue
@Column(name="id")
@Transient
session.save(obj)
session.get(X.class, id)
@Embeddable
@OneToOne
@OneToMany
@ManyToOne(MappedBy="")
@ManyToMany(MappedBy="")
@Cacheable

Testing
